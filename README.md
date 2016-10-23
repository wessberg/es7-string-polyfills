## Polyfills for String.prototype.padStart and String.prototype.padEnd

Based on the reference implementation by [tc39](https://github.com/tc39) found [here](https://github.com/tc39/proposal-string-pad-start-end/blob/master/polyfill.js).

### Install
Install with
```javascript
npm install es7-string-polyfills --save-dev
```

### Usage
Load it in your code with an import statement:
```javascript
import "es7-string-polyfills";
```
Or from a script tag:
```html
<script src="../node_modules/es7-string-polyfills/polyfill.min.js"></script>
```

The polyfills will be applied automatically if necessary.
