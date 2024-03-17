# JavaScript
  - a versatile programming language that adds interactivity and dynamism to webpages
  - just-in-time compiled programming language
    1. it's interpreted line by line
    2. it dynamically analyzes code as it runs
    3. The engine doesn't compile the entire script before running it; instead, it optimizes and compiles parts of the code right before they are about to be executed.
  - ECMAScript (same as JavaScript)

# Primitive Data Types
  - Boolean
    1. True
    2. False
  - Number
  - String
    1. surrounded by "" or ''
  - Symbol
  - Null
  - Undefined
  - bigInt

# Arithmetic Operators
  - `+` addition
  - `-` subtraction
  - `*` multiplication
  - `/` division
  - `%` modulo

# Assignment Operators
 - `+=` addition assignment
 - `-+` subtraction assignment
 - `*=` multiplication assignment
 - `/=` division assignment

# Variables
  - Used whenever there is a need to store a piece of data

# Keywords
  - Used to declare, name, variables
  1. let - can be reassigned
  2. const - cannot be reassigned, constant
  3. var - used before 2016, variable. Can be reassigned

# Random Terms/Info
  - parameter - What's inside the () of a function
  - in console.log(), console is the object and log() is the function
  - log is a built-in method, or function, of log
  - log is a property of console
  - alert()--output on the page as a pop-up
  - JavaScript is zero-based
  - node name - another name for elements or tags
  - string.length - The length property returns the number of characters that make up the string

# String Concatenation
  - combining strings using +
  - ex. console.log("Secelia" + "McNair");
  - to add a space, console.log("Secelia" + "" + "McNair");

# String Interpolation
  - a way of combining data types using template literals
  - uses `` backticks
  - `let firstName = "Secelia"`
    `let lastName = "McNair"`
    `console.log(\`My name is ${firstName} ${lastName}\`)`

# Variable
  - can have any name
  - camelCase
  - should be descriptive

# DOM
  - document object model
  - allows interaction with the content, structure and style of HTML docs
  - innerHTML--whatever text is between the opening and closing tags of an element
  - document.querySelector
  - document.querySelectorAll
  - document.getElementById
  - document.getElementsByClassName
  - array.length
  - array[0].style = "color: pink;"--can manipulate CSS in JavaScript
  - `window.onload = function() {
    alert("alert");
  }`--alert pops up at the loading of the page
  - modern way to write this:
  window.addEventListener("load", function() {
    alert("alert");
  })

# Methods
  - Return information about an object
  - Are called by appending an instance with a period, the method name, and parentheses
  - `Math.random();`--random is the method. 
  - function is used interchangably 

# Built-in Objects
  - contain methods that can be called by appending the object name with a period, the method name, and a set of parentheses
  - in `Math.random();`, Math is the built-in object

# Math Methods
  ## Math.random()
    - returns a floating-point, random number in the range from 0 up to but not including 1
  ## Math.floor()
    - returns the largest integer less than or equal to the given number
    - `console.log(Math.floor(5.95));`--output is 5
  ## Math.round()
    - rounds using normal conventions
  ## Math.ceil()
    - rounds up

# Events
  - In JavaScript, events refer to actions or occurrences that happen in a web page, such as a user clicking a button, pressing a key, or the page finishing loading. These events trigger JavaScript code to run.
  - events:
    1. click
    2. dblclick
    3. mouseover
    4. mouseout
    5. keydown
    6. focus
    7. blur
    8. there are many others. Check MDN.