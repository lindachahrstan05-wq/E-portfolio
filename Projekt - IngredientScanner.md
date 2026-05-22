# Utveckling av en webapp - IngredientScanner

Tillsammans med 5 andra studenter utvecklade vi en web applikation där man som användare kan scanna innehållsförteckningen på olika livsmedel och få varningar för de E-ämnen som man valt i sin preferens lista. Vi har satt upp en lista med alla E-ämnen som finns på Livsmedelsverket och där man som användare kan välja de E-ämnen som man inte vill ska finnas i de livsmedel man köper. Scanner funktionen kan scanna innehållsförteckningen eller streckkoden på livsmedlet.

---
Denna del visar procent andelen av hur mycket av användarens preferenser som matchar de E-ämnen som finns i livsmedlet
```tsx
const warningsCount =
    results.warnings.eNumbers.length + results.warnings.food.length

  const otherCount = results.other.eNumbers.length + results.other.food.length

  const totalCount = warningsCount + otherCount

  const warningsPercentage = (warningsCount / totalCount) * 100
```
---
Bilder på startsidan av webappen och en varningssidan efter scanningen
<p align="center">
<img src="images/startsida.png" width="300">
    <img src="images/varningssida.png" width="500">
</p>

---

Länk till git repot där all kod finns
[GitHub Repository](https://gits-15.sys.kth.se/lincha/Ansmark)

Länk till webappen
[Scaneat.se](https://www.scaneat.se/)
