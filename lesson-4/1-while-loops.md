# While Loops

```js
/** While Loop */
const numbers = [1, 2, 3, 4, 5, 6];
let index = 0;
let total = 0;

while (index < numbers.length) {
  total += numbers[index];
  index++;
}

console.log(total); // 21

/** Another example */
const numbers = [1, 2, 3, 4, 5, 6];
let index = 0;
let total = 0;

while (index < numbers.length && !(numbers[index] % 2)) {
  console.log(numbers[index]);
  index++;
}
```
