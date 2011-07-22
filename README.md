# jQuery.autoalign.js

### What is jquery.autoalign.js?
a jQuery plugin that conveniently aligns the elements of your page automatically.

### Basic implementation
```javascript
$(document).ready(function() {
   $("#b").autoalign('center middle');
});
```
_the code above will center your box horizontally and vertically_

### Method overview

```$(elem).autoAlign( location, options );```

- **location** _: String_ available values are "top", "left", "right", "bottom", "center", "middle"
- _options_ **offsetX** offset value of the element in the x-axis
- _options_ **offsetY** offset value of the element in the y-axis

#### Online example ####
[http://jquery.autoalign.jamesflorentino.com](http://jquery.autoalign.jamesflorentino.com)

### Thanks to ###
Thanks to [Rico Sta. Cruz](https://github.com/rstacruz) for suggesting to convert my original code to jQuery.

### @author ###
James Florentino, _Interactive Designer_