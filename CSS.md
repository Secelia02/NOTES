# CSS Formatting
- selector {
  property: value;
}
- use a semicolon at the end of each line

# How to link CSS to HTML
- `<link rel="stylesheet" href="style.css">`

# Text Align

- `h1 {
  text-align: center;
}`
  _text-align: left | right | center | justify | initial | inherit_

# Text Decoration

- `h1 {
  text-decoration: underline;
}`

1. none: no line is drawn, and any existing decoration is removed.
2. underline: draws a 1px line across the text at its baseline.
3. line-through: draws a 1px line across the text at its “middle” point.
4. overline: draws a 1px line across the text, directly above its “top” point.
5. inherit: inherits the decoration of the parent.

# Font Size

- `body {
  font-size: 18px;
}`

# Font Weight

- `h1 {
  font-weight: normal;
}`

- `p {
  font-weight: 700;
}`

- `a {
  font-weight: 100;
}`
  _Note: font-weight: normal | bold | bolder | lighter | number | initial | inherit; It can also be a value between 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900 where 100 is thin and 900 is extra bold_

# Color Property

- `p {
  color: #00ff00;
}`

## Native colors

- `h1 {
  color: blueviolet;
}`
  _Note: We generally only use black or white. Other colors such as red, blue, green are only good for testing purposes. You should use Hexadecimal values instead._

## Hexadecimal colors

- `h1 {
  color: #885df1;
}`
  _Use a color picker to find the color you need.
  Note: #000000 is black, #ffffff is white. #ffffff is the same as #fff, #FFFFFF or #fff or white._

## RGB Colors
- /* without transparency */
`p {
  color: rgb(135, 93, 241);
}`

/* with transparency */
`h1 {
  color: rgba(135, 93, 241, 0.5);
}`
*The RGB color model defines a given color according to its red, green, and blue components. An optional alpha component represents the color's transparency. The first 3 values should be between 0 and 255 and the fourth between 0 and 1. 0 being completely transparent.*

# Background
- `.header {
  background: green;
}`
*You can use an image as a background*

# Line Height
`h1 {
  line-height: 28px;
}`

`p {
  font-size: 14px;
  line-height: 1.5;
}`
*Note: We generally use a multiplier such as 1.5 which making the line height 1.5 times higher than the font size*

# Margin
- /* Margin around the element */
`.box-1 {
  margin: 10px;
}`

/* Margin left only */
`.box-2 {
  margin-left: 10px;
}`

/* 10px margin on top and bottom, 5px on the sides */
`.box-3 {
  margin: 10px 5px;
}`

/* 20px margin top, 15px margin right, 10px margin bottom and 5px margin left */
`.box-4 {
  margin: 20px 15px 10px 5px;
}`
*Space outside an element.*

# Padding
- /* padding around the element */
`.box-1 {
  padding: 10px;
}`

/* padding left only */
`.box-2 {
  padding-left: 10px;
}`

/* 10px padding on top and bottom, 5px on the sides */
`.box-3 {
  padding: 10px 5px;
}`

/* 20px padding top, 15px padding right, 10px padding bottom and 5px padding left */
`.box-4 {
  padding: 20px 15px 10px 5px;
}`
*Space inside an element.*

# Border
- `.header {
  border: 1px solid #885df1;
}`
*First value is the thickness, second one the style (none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset), and third one is the color.*

# Border-radius
- /* Light rounded corners all around the element */
`.box-1 {
  border-radius: 20px;
}`


/* Rounded corner top left and right only */
`.box-2 {
  border-radius: 50% 50% 0 0;
}`
*The border-radius CSS property rounds the corners of an element's outer border edge.*

# Box Shadow
- `.box {
  box-shadow: 10px 5px 5px red;
}`
*the third value is the blur radius and the last value is the shadow color*

# CSS Selectors
- class - use a "." in front of it
- id - use a "#" in front of it
- "*" - all elements
- element
- element, element - selects multiple elements to have the same formatting
- element element - selects all p tags for instance inside of h2
- element>element - selects all p tags that have a parent of h2
- element+element - selects any p element that is exactly after an h2
- :hover
- :first-child - targets the first child element of its parent
- :last-child - targets the last child element of its parent

# Box Model
1. Margin - on the outside
2. Border 
3. Padding - around the content
4. Content


# Flexbox

# Custom Fonts
- google fonts
- to ensure the user can see them, include the link in my html head and in the css file

# Resources
- css tricks website
- paletton color picker
