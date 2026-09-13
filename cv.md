# Irina Filimonova
Junior Frontend Developer

## Contact information
* E-mail: alpinawhite2@gmail.com
* Discord: flllmonova

## Briefly about myself
My goal is to learn the technical stack for frontend development and learn how to develop websites and applications at a high level.

## Skills
* **`HTML5`**;
* **`CSS3`**;
* **`JavaScript (basics)`**;
* **`Git`**;
* **`Github`**;
* **`Figma`**;
* **`Adobe Photoshop`**.

## Code Examples
Kata «RGB To Hex Conversion» from Codewars
> The rgb function is incomplete. 
> Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. 
> Valid decimal values for RGB are 0 - 255. 
> Any values that fall out of that range must be rounded to the closest valid value.

```
function cakes(recipe, available) { 
  const result = [];
  
  for (let item in recipe) {
    if (item in available) {
      const n = Math.floor(available[item] / recipe[item]);
      result.push(n);
    } else {
      return 0;
    }
  }
  
  return result.reduce((min, item) => (min < item) ? min : item);
}
```