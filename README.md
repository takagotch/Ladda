### Ladda
---
https://github.com/hakimel/Ladda

```
<button class="ladda-button" data-style="expand-right"><span class="ladda-label">Submit</span></button>
```

```js
import * as Ladda from 'ladda';

var l = Ladda.create( document.querySelector( '.my-button') );
l.start();
l.setProgress( 0.5 );
l.stop();
l.toggle();
l.isLoading();
l.remove();

Ladda.bind( 'button[type-submit]' );
Ladda.bind( 'button[type=submit]', { timeout: 2000 });

Ladda.stopAll();
```

```
```

