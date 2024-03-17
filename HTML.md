# Creating an HTML document

- Use an html extension
- Home page should be index.html
- Use the `!` (bang symbol) then 'tab' to format the html document
- Update the title
- HTML goes inside the body

# HTML Elements

- tag
  : a keyword that tells a web browser how to format and display a web page. Tags are a set of characters that provide instructions for the visual content on a web page
- element
  : a part of a webpage that tells a web browser how to structure and interpret a part of the HTML document. HTML elements can contain formatting instructions, semantic meaning, and content and are made up of tags (the tag plus the content inside the tag)
- `<h1></h1>` through `<h6></h6>`(header tags)
- `<ul></ul>`(unordered list) with `<li></li>`(list) inside
- `<ol></ol>` (ordered list) with `<li></li>`(list) inside
- `<p></p>`
- `<div></div>`
- `<span></span>`
- `<button></button>`
- `<br>` (break) a self-closing tag
- `<img>` (image) a self-closing tag
- `<strong></strong>` (bold)
- `<em></em>` (italicized)
- `<hr>` (horizontal line) a self-closing tag
- `<a href="https://www.google.com>New Page</a>` an anchor tag. makes hyperlinks

# Attributes

- attribute
  : a markup language feature that can change the behavior or display of an HTML element. Attributes are used by including them in an opening HTML tag
- src
- class
- id
- href

# Div

- `<div>SheCodes</div>`
  `<div class="coding-workshop">SheCodes</div>`
  _Generally used to add a class around some content and target that class from CSS. It doesn't add any styling on its own._
  _Block element_

# Section

- `<section class="workshop-information">
<h2>SheCodes Pro</h2>
<p>SheCodes Pro includes everything you need to become a professional developer...</p>
</section>`
*It typically groups information on a page. It's very similar to <div> but less commonly used. It doesn't add any styling on its own.*
*Note: Block element*

# Header

- `<header class="page-header">
<h1>SheCodes Workshops</h1>
</header>`
*It typically groups the introduction of the page or the navigation. It doesn't add any styling on its own.*
*Note: Block element*

# Footer

- `<footer>
  <p>© SheCodes</p>
   </footer>`
   *It typically groups information about the author of the section, copyright data, or links to related documents. It doesn't add any styling on its own.*
   *Note: Block element*

# Span
- `<span>SheCodes</span>`
`<span class="best-workshop">SheCodes</span>`
*Generally used to add a class around some content (especially text and images) and target that class from CSS. It doesn't add any styling on its own.*
*Note: Inline element*

# Line Break
- `SheCodes offers coding workshops <br />
to busy women <br />
Sign up today`

# Image
- `<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" />`
`<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" alt="Image description" />`
`<img src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/083/182/original/cat.png?1685030491" alt="Image description" width="400" />`
- local image: `<img src="images/cat.png" />`
*Adds an image to the page*

# Audio
- `<audio controls src="https://url-to-audio-file.mp3"></audio>`
*Adds audio to the page*

# Video
- `<video src="https://video-url"></video>`
`<video src="https://video-url" controls></video>`
*Adds a video to the page*

# Form
- `<form action="mailto:recipient@example.com"  method="get" enctype="text/plain">
    <label for="name">Enter your name: </label>
    <input type="text" placeholder="Your name" name="name" id="name" required />
    <label for="email">Enter your email: </label>
    <input type="email" placeholder="Your email" name="email" id="email" required />
    <input type="submit" value="Subscribe!" />
</form>`
- Here are some examples of input types:
  1. Text: A one-line text input field
  2. Password: A one-line password input field
  3. Submit: A submit button to send the form to the server
  4. Reset: A button to reset all values in the form
  5. Radio: A radio button that allows the user to select one option
  6. Checkbox: A checkbox that allows the user to select multiple options
  7. Button: A simple push button
  8. Color: An input field that contains a color
- Other examples of input types include:
  1. Sliders
  2. Date/time pickers
  3. Range inputs
  4. Email address field
  5. Search field
  6. Phone number field
  7. URL field
  8. Numeric field
- Dropdown menu
  1. `<select>`
  2. `<option value="volvo">Volvo</option>`
  3. `<option value="audi">Audi</option>`
  4. `<select>`

# Link
- `<a href="https://www.shecodes.io/">SheCodes</a>`
`<a href="https://www.shecodes.io/" target="_blank">SheCodes</a>`
`<a href="https://www.shecodes.io/" target="_blank" title="SheCodes Website">SheCodes</a>`
*Adds a link to a page*
*Note: target="_blank" opens the link in a new window.*

# External CSS
- `<head>
    <link rel="stylesheet" href="style.css" />
</head>`
*Add the link tag inside the head tags*

# External JavaScript
- `<body>
  <h1>
    SheCodes
  </h1>
  <script src="app.js"></script>
</body>`
*Add right before closing the body*

# !DocTYPE
  - a declaration
  - an instruction to the web browser about what version of HTML the page is written in

# index.html
  - common practice to use it as your homepage

# Relative and Absolute Paths
  - relative can't be accessed outside of your computer
  - absolute can be accessed outside of your computer. No matter where you reference is, it takes you to the site

# Additional Info
  - ctrl + / to comment
  - ctrl + U or view source will allow you to copy a website
