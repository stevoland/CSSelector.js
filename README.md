# CSSelector.js

Generate a CSS selector string to target the given node

## Installation

You can use with an AMD loader or vanilla javascript.

### Dowload
You can directly download the
[Development Version](https://raw.github.com/stevoland/CSSelector.js/master/dist/CSSelector.js)
or the
[Production Version](https://raw.github.com/stevoland/CSSelector.js/master/dist/CSSelector.min.js)
from the root folder

### BOWER
```shell
$ bower install CSSelector.js
```

### JAM
```shell
$ jam install CSSelector.js
```

## Integration

### AMD
```javascript
// AMD
require(['path/to/CSSelector.js'], function (CSSelector) {
  // CSSelector(el);
});
```

### CommonJS
```javascript
// CommonJS
var CSSelector = require('CSSelector');
```

### Vanilla JS
```html
<!-- Vanilla javascript -->
<script src="path/to/CSSelector.js"></script>
<script>
	console.log(CSSelector(el));
</script>
```

