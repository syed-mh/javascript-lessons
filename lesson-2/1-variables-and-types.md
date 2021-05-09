# Variables and Types

## Overview

- Variables are used to store and manipulate data
- Variables do not have inherent data types
- Data types of most variables can be changed at any point in the code

## Conventions & Rules

- Variable names in JavaScript are typically written in `camelCase` or `PascalCase`
- Variable names like `variable_name` are valid but are generally discouraged
- Variable names must start with an `_` (underscore) or a letter

## Types of Variables

### `VAR`

- Original keyword to declare a variable in JavaScript
- Mutable and reassignable
- Can be declared as an empty variable
- Discouraged as of `ES6 (ES2015)`

### LET

- Essentially a replacement and improvement on `var`
- Mutable and reassignable
- Can be declared as an empty variable

### CONST

- New type of variable introduced in `ES6 (ES2015)`
- Mutable but not reassignable
- Cannot be declared as an empty variable

## Code Example

```javascript
/** var keyword */

/**
 * Valid: can be declared without a value
 */
var myVariableName;

/**
 * Valid: can be assigned a value later
 */
myVariableName = 2;
/**
 * Valid: can then be assigned a value of a different data type
 */
myVariableName = "My Variable";

/** let keyword */

/**
 * Valid: can be declared without a value
 */
let myOtherVariable;
/**
 * Valid: can be assigned a value later
 */
myOtherVariable = 2;
/**
 * Valid: can then be assigned a value of a different data type
 */
myOtherVariable = "My Variable";

/** const keyword */

/**
 * Invalid: can not be declared without a value
 */
const myConstant; // invalid
/**
 * Valid: can be assigned a value of any data type
 */
const myConstant = 2;
const myConstant = "My Constant";
/**
 * Invalid: can not be re-assigned a value
 */
myConstant = "Other Constant Value";
```