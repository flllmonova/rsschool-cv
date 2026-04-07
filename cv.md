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
Kata «Pete, the baker» from Codewars
> Write a function cakes(), which takes the recipe (object) and the available ingredients (also an object)
> and returns the maximum number of cakes Pete can bake (integer).
> For simplicity there are no units for the amounts (e.g. 1 lb of flour or 200 g of sugar are simply 1 or 200).
> Ingredients that are not present in the objects, can be considered as 0.

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

## Courses
* HTML5, CSS3 and JavaScript by code-basics.com;
* JS / Front-end Pre-school (in progress);

## Languages
* English (A1);
* Russian (native).
