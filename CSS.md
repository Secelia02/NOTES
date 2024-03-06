# CSS Formatting

- use a semicolon at the end of each line

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
