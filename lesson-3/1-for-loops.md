# For Loops

```js
/** For Loop */
const numbers = [1, 2, 3, 4, 5, 6];
let total = 0;

for (let index = 0; index < numbers.length; index++) {
  total += numbers[index];
}

console.log(total); // 21

/** Another example */
const numbers = [1, 2, 3, 4, 5, 6];
let total = 0;

for (let index = 0; index < numbers.length; index++) {
  if (!(numbers[index] % 2)) total += numbers[index];
}

console.log(total);
```

# Break & Continue Statements

- Break
- Continue

```js
/** Continue */
const numbers = [1, 2, 3, 4, 5, 6];
let total = 0;

for (let index = 0; index < numbers.length; index++) {
  if (numbers[index] % 2 > 0) continue;
  total += numbers[index];
}

console.log(total); // 12

/** Break */
const numbers = [1, 2, 3, 4, 5, 6];
let total = 0;

for (let index = 0; index < numbers.length; index++) {
  if (numbers[index] % 2 > 0) break;
  total += numbers[index];
}

console.log(total); // 0
```
