# Kasta tärning i javascript #

## HTML ##
Följande html-kod gör tre saker
1. Anger bas-adressen för bilderna
2. Skapar en knapp kopplad till en js-funktion
3. Visar en tärningsbild

```html
<base href="https://coderdojofalkenberg.github.io/assets/img/">
<button onclick="rolldice()">
Kasta tärningen
</button>
<img id="diceimg" src="Dice-1.png" />
```

## Javascript ##

För att man ska komma åt funktionen från knappen behöver man ändra "Load Type" till "No wrap - in head"

```javascript
function rolldice()
{
  // slumpa nytt tal mellan 1 och 6
  
  // byt bild
  document.getElementById('diceimg').src="Dice-2.png";
}
```
