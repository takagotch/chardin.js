### chardin.js
---
https://github.com/heelhook/chardin.js

```
<link href="chardinjs.css" rel="stylesheet">
<script src="chardinjs.min.js"></script>

<img src="img/chardin.png" data-intro="An awesome 18th-century painter, who found beauty in everyday, common things.">
```

```
rake compile
```

```js
$('body').chardinJs('start')
$('.container').chardinJs('start')

var chardinOverlay = $('body').chardinJs('start');
chardinOverlay.refresh();
```

