![web component logo](http://i49.tinypic.com/e7nj9v.png)

# getAttribute

A cross-browser implementation of getAttribute.

Source found here: [http://stackoverflow.com/a/3755343/361337](http://stackoverflow.com/a/3755343/361337)
written by [Vivin Paliath](http://stackoverflow.com/users/263004/vivin-paliath)

Uses default `getAttribute` if it's available.

## Installation

    $ component install javve/get-attribute

## Example

```html
<div id="test" data-value="myValue"></div>
```

```js
var getAttribute = require('get-attribute');

var el = document.getElementById('test')
var dataValue = getAttribute(el, 'data-value');

alert(dataValue); // Alerts "myValue"
```

## API

### getAttribute(element, attribute)

Return the value for `attribute` at `element`.

## License

MIT
