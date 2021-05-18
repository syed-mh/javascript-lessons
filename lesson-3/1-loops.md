# Loops

- For loops
- While loops

```js
/** For Loop */
const numbers = [1,2,3,4,5,6]
let total = 0;

for(let index = 0; index < numbers.length; index++) {
  total += numbers[index]
}

console.log(total) // 21

/** While Loop */
const numbers = [1,2,3,4,5,6]
let index = 0;
let total = 0;


while(index < numbers.length)
  total += numbers[i]
  index++;
}

console.log(total) // 21
```

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