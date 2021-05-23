# Do-While Loops

```js
/** While Loop */
const numbers = [1, 2, 3, 4, 5, 6];
let index = 0;
let total = 0;

do {
  console.log(numbers[index]);
} while (index < numbers.length && !(numbers[index] % 2));
{
  total += numbers[index];
  index++;
}
```
