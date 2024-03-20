# Definition
  - a variable that can have multiple values assigned to it
  - these values are called *elements*.

# pop(), push(), shift(), unshift()
  - pop() and push() are for the end of an array
  - pop() removes an element from the end of an array
    1. arrayName.pop()
  - push() adds one or more elements to the end of an array
    1. arrayName.push("element1", "element2")
  - shift() and unshift() are for the beginning of an array
  - shift() method removes an element from the beginning of an array
    1. arrayName.shift()
  - unshift() adds one or more elements to the beginning of an array
    1. arrayName.unshift("element1", "element2")
  - You can assign the removed element to a variable
    1. let removedElement = arrayName.shift()

# splice()
  - use to insert one or more elements anywhere in an array, while optionally removing one or more elements that come after it
    1. `const pets = ["dog", "cat", "fly", "bug", "ox"];`
    2. `pets.splice(2, 2, "pig", "duck", "emu");`
    3. The first number is the index number. It tells you the insertion point
    4. The second number tells the number of elements to remove after the insertion point
    5. following are the new elements to insert
  - You can make additions without removing any elements
    1. `const pets = ["dog", "cat", "fly", "bug", "ox"];`
    2. `pets.splice(2, 0, "pig", "duck", "emu");`
    3. the 2 is the insertion point
    4. the 0 means to remove no elements
    5. Following are the elements to insert
  - You can also remove elements without adding any
    1. `pets.splice(2, 2);`

# slice()
  - Use the slice() method to copy one or more consecutive elements of an array and create a new array comprising of the copied elements
    1.  `const pets = ["dog", "cat", "fly", "bug", "ox"];`
    2. `const oddPets = pets.splice(2, 4);`
    3. The first number is the index of the first element to be copied
    4. The second number is the index of element *after* the last element to be copied
    5. `["fly", "bug"]`
    6. the original array isn't changed by the operation. slice() just copies
  - If all the elements after the indexed one is copied, you can omit the second index
    1. `const oddPets = pets.slice(2);`
  - You can use the slice() method to alter an array but the array must use the keyword `let` to do so
    1. `let pets = ["dog", "cat", "fly", "bug", "ox"];`
    2. `pets = pets.slice(1, 3);`
    3. `["cat", "fly"];`

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