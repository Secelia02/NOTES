# Definition
  - a variable that can have multiple values assigned to it
  - these values are called *elements*.

# Conventions
  - const is the preferred method to declare an array
  - `const cities = ["Seoul", "Paris", "Hawaii"];`
  - the variable of an array is typically plural
  - the elements that are strings are surrounded in quotes, comma, then a space. Number values do not have quotes
  - enclosed with brackets
  - elements are zero-based in their counting so in the above example Seoul is indexed at 0, Paris at 1, and Hawaii at 2.
  - cities[0] is how you name an element in an arry
  - the '0' is called the *index*.
  - array elements can be variables
    1. `let a = 30;`
    2. `let b = 45;`
    3. `const someNumbers = [a, b, 99];`
  - You can declare an array without assigning it any values
  - You can assign elements to an empty array using index numbers
   1. `const someNumbers = [];`
   2. `someNumbers[0] = 15;`
   3. `someNumbers[1] = 25;`
  - you can replace numbers the same way