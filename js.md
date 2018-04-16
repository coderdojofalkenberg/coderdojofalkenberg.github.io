# Översättning Scratch -> .js #


![Slumptal](/assets/img/random_block.png)
## Slumptal-blocket ##
```javascript
// Slumpa ett tal  
function slumptal(min, max){  
  return Math.floor(Math.random()*(max-min+1)+min);  
}  

var tal = slumptal(1, 10);
```
Länk till en js-fiddle för [Slumptal](https://jsfiddle.net/oghvkbt1/)

