# Översättning Scratch -> .js #


## Slumptal-blocket ##
![Slumptal](/assets/img/random_block.png)
```javascript
// Slumpa ett tal  
function slumptal(min, max){  
  return Math.floor(Math.random()*(max-min+1)+min);  
}  

var tal = slumptal(1, 10);
```
Länk till en js-fiddle för [Slumptal](https://jsfiddle.net/oghvkbt1/)


## OM-blocket ##
![Om](/assets/img/if_block.png)
```javascript
// Jämföra om x är mindre än 10
if (x < 10){
  alert('X är mindre än 10');
} else {
  alert('X är INTE mindre än 10');
}
```
Länk till en js-fiddle för [Om](https://jsfiddle.net/k1wLbjqd/1/)

