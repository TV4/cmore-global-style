# cmore-global-style

npm package for global styles like color and space.

https://www.npmjs.com/package/cmore-global-style

__space__

  Return the space by a multiple of 8 pixels as string. ('0', '8px', '16px'...)

__colors__

  List standard colors used in C More:
  
![mora](https://imageproxy.b17g.services/convert?source=https%3A%2F%2Fdummyimage.com%2F16x16%2FFFFFFF%2FFFFFFF.png&resize=15x15&bgcolor=000000&bgheight=17&bgwidth=17&shape=cut)
white: '#FFFFFF'

![mora](https://dummyimage.com/16x16/000000/000000.png)
black: '#000000'
      
![mora](https://dummyimage.com/16x16/FF3334/FF3334.png)
mora: '#FF3334'

![mora](https://dummyimage.com/16x16/DA2B2C/DA2B2C.png)
moraShadow: '#DA2B2C'

![mora](https://dummyimage.com/16x16/1C7CE5/1C7CE5.png)
stockholm: '#1C7CE5'

![mora](https://dummyimage.com/16x16/165DAA/165DAA.png)
stockholmShadow: '#165DAA'

![mora](https://dummyimage.com/16x16/F5F5F5/F5F5F5.png)
ystad: '#F5F5F5'

![mora](https://dummyimage.com/16x16/E6E6E6/E6E6E6.png)
kalmar: '#E6E6E6'

![mora](https://dummyimage.com/16x16/A3A3A3/A3A3A3.png)
karlstad: '#A3A3A3'

![mora](https://dummyimage.com/16x16/323232/323232.png)
haparanda: '#323232'

![mora](https://dummyimage.com/16x16/1B1B1B/1B1B1B.png)
jokkmokk: '#1B1B1B'

![mora](https://dummyimage.com/16x16/5a5a5a/5a5a5a.png)
sundsvall: '#5a5a5a'

![mora](https://dummyimage.com/16x16/75AE3C/75AE3C.png)
checkmark: '#75AE3C'

Example usage:

```js
var style = require("cmore-global-style")

var sizeInPixels = style.space(2))


var colorRed = style.colors.mora
```

Will return a string containing '16px'. The given parameter will return the given space in pixels multiple of 8
