# If statements

```js
/** If Statement */
let condition = true;

if (condition === true) console.log("the condition is true");
// Output: 'the condition is true'

if (condition) console.log("the condition is true");
// Output: 'the condition is true'

condition = false;

if (condition) console.log("the condition is true");
// No Output

if (!condition) console.log("the condition is false");
// Output: 'the condition is false'
```

# Else statements

```js
/** Else statements */
const grades = [56, 95];

if (grades[0] > grades[1]) {
  console.log(`The first grade is higher: ${grades[0]}`);
} else {
  console.log(`The second grade is higher: ${grades[1]}`);
}
// Output: 'The second grade is higher: 95'
```

# Else If Statements

```js
const department = "development";

if (department === "accounts") {
  console.log("You are an accountant");
} else if (department === "development") {
  console.log("You are a developer");
} else if (department === "photography") {
  console.log("You are a photographer");
} else {
  console.log("I have no idea what you do");
}

// Output: 'You are a developer'
```
