# Kasta tärning i javascript #

```html
<base href="https://coderdojofalkenberg.github.io/assets/img/">
<button onclick="rolldice()">
Kasta tärningen
</button>
<img id="diceimg" src="Dice-1.png" />
```

```javascript
function rolldice()
{
	// slumpa nytt tal mellan 1 och 6
  
  // byt bild
  document.getElementById('diceimg').src="Dice-2.png";
}
```
