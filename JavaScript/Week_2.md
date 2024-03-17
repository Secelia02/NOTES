# Control Flow
  - The order in which statements are executed in a program
  - The default is from left to right, top to bottom
  - conditionals, like if statements, alter control flow

# Truthy and Falsy
  - Values that evaluate to `true` are known as truthy
  - Values that evaluate to `false` are known as falsy
  - falsy values include `false`, `0`, empty strings, `null`, `undefined`, and `NaN`. All other values are truthy

# Logical Operators
  ## `||` the logical OR operator 
    - checks two values and returns a boolean
    - if one or both values are truthy, it returns true
    - if both are falsy, it returns false
  ## `&&` the logical AND operator
    - checks two value and returns a Boolean
    - if both values are truthy, it returns true
    - if one or both of the values is falsy, it returns false
  ## `!` the logical NOT operator
    - invert a Boolean value
    - invert the truthiness of non-Boolean values

# Comparison Operators
  - Used to compare two values and return `true` or `false` depending on the validity
  - `===` strict equal
  - `!==` strict not equal
  - `>` greater than
  - `>=` greater than or equal
  - `<` less than
  - `<=` less than or equal

# `if` Statement
  - An `if` statement accepts an expression with a set of parentheses:
    1. If the expression evaluates to a truthy value, then the code within its code body executes.
    2. If the expression evaluates to a falsy value, its code body will not execute.
    3. `const isMailSent = true;
    if (isMailSent) {
    console.log('Mail sent to recipient');
    }`

# `else` Statement
   - the `else` block will be executed only if the `if` condition fails
   - `const isTaskCompleted = false;
   if (isTaskCompleted) {
    console.log("Task completed");
   } else {
    console.log("Task incomplete");
   }

# `else if` Clause
   - if there are more than 2 conditions, an `else if` block can be added
   - `else` would always be last

# Ternary Operator
  - compact syntax when choosing between 2 choices
  - it accepts a condition followed by a `?` operator, and then 2 expressions separated by a `:`.
  - if the condition evaluates to truthy, the first expression is executed
  - otherwise the second expression is executed
  - `let price = 10.5;
  let day = "Monday";

  day === "Monday" ? price -= 1.5 : price += 1.5;`

# `switch` Statement
  - it provides a means of checking an expression against muse `case` clauses. 
  - if the case matches, the code inside the clause is executed
  - the `case` clause should finish with a `break` keyword
  - if no case matched but a `default` clause is included, the code inside the `default` will be executed
  - `const food = "salad";

  switch (food) {
    case "oyster":
    console.log("The taste of the sea");
    break;
    case "pizza":
    console.log("A delicious pie");
    break;
    default:
    console.log("Enjoy your meal");
  }`

  
  