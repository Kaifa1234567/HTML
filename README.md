1. Basic Structure of an HTML Document

An HTML document is divided into several parts:

<!DOCTYPE html>: This declaration tells the browser that the document is HTML5.

<html>: This is the root element that contains all the HTML code.

<head>: Contains meta-information about the document (like title, character set, linked stylesheets).

<body>: Contains the content that is displayed on the webpage.


Example:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8"> <!-- Character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsive design -->
    <title>My Webpage</title> <!-- Title displayed in the browser tab -->
  </head>
  <body>
    <h1>Welcome to My Webpage!</h1>
    <p>This is a paragraph of text.</p>
  </body>
</html>


---

2. HTML Elements and Tags

HTML is built using elements, which are written with tags. Tags usually come in pairs: an opening tag (e.g., <p>) and a closing tag (e.g., </p>). Some elements are self-closing, like <img /> for images.

Common HTML Elements:

Headings: <h1>, <h2>, ... <h6> (Used to define headings of different levels)

<h1>Main Heading</h1>
<h2>Subheading</h2>

Paragraphs: <p> (Used to define paragraphs)

<p>This is a paragraph.</p>

Links: <a> (Used to create hyperlinks)

<a href="https://example.com">Visit Example</a>

Images: <img> (Used to embed images, self-closing)

<img src="image.jpg" alt="A descriptive text" />

Lists: <ul> (unordered list), <ol> (ordered list), <li> (list item)

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

Tables: <table>, <tr>, <th>, <td>

<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
</table>



---

3. Attributes

HTML elements can have attributes that provide additional information. For example, the <a> tag has the href attribute to specify the destination URL.

<a href="https://example.com" target="_blank">Visit Example</a>

Some common attributes:

id: Specifies a unique identifier for an element (e.g., <div id="main"></div>).

class: Specifies one or more class names, often used for styling or scripting (e.g., <div class="container"></div>).

src: Specifies the source of an image or video (e.g., <img src="image.jpg" />).

alt: Describes an image (e.g., <img src="image.jpg" alt="Description" />).



---

4. Forms and Input

Forms are used to collect user input. They use <form>, <input>, <textarea>, <select>, and other form elements.

Example of a simple form:

<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
  <br>
  <button type="submit">Submit</button>
</form>

<form>: Defines the form.

action: Specifies where to send the form data when submitted.

method: Defines the HTTP method to send the data (usually GET or POST).

<input>: Defines input fields (like text fields, checkboxes, etc.).

<button>: Defines a clickable button.



---

5. Semantic Elements

HTML5 introduced semantic elements that make the structure of the page clearer for both browsers and developers. These elements also help with SEO and accessibility.

Examples of semantic elements:

<header>: Represents the introductory content of a page or section.

<footer>: Represents the footer section of a page or section.

<article>: Represents a self-contained piece of content that could stand alone.

<section>: Represents a section of a document, often with its own heading.

<nav>: Represents navigation links.


Example:

<header>
  <h1>Website Title</h1>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
</header>

<article>
  <h2>Article Title</h2>
  <p>This is the content of the article.</p>
</article>

<footer>
  <p>© 2025 Your Website</p>
</footer>


---

6. HTML Comments

You can add comments in HTML to describe the code or make notes for yourself and other developers. They don’t appear on the page.

Example:

<!-- This is a comment -->
<p>This is a paragraph.</p>


---

Conclusion

HTML is the foundation of web development. It helps you structure content, create links, embed images, and display information in an organized way. After getting comfortable with HTML, you can start enhancing the look and feel of your webpage using CSS (Cascading Style Sheets) and add interactivity with JavaScript.
