# Switch Statements

```js
const department = "development";

/** Common switch statement syntax */
switch (department) {
  case "accounts":
    console.log("You are an accountant");
    break;

  case "development":
    console.log("You are a developer");
    break;

  case "photography":
    console.log("You are a photographer");
    break;

  default:
    console.log("I have no idea what you do");
    break;
}

/** Hacking strict comparison into switch statements */
switch (true) {
  case department === "accounts":
    console.log("You are an accountant");
    break;

  case department === "development":
    console.log("You are a developer");
    break;

  case department === "photography":
    console.log("You are a photographer");
    break;

  default:
    console.log("I have no idea what you do");
    break;
}
```
