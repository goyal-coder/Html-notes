HTML Basics
Overview
HTML stands for Hypertext Markup Language, which is the standard markup language used for creating web pages. HTML describes the structure of a web page and is made up of elements, which tell the browser how to display content such as headings, paragraphs, links, and images.

Key Concepts
1. HTML Tags & Elements
HTML elements consist of:

Start tag: Marks the beginning of an element (e.g., <p>).
End tag: Marks the end of the element (e.g., </p>).
Content: The actual data inside the tags (e.g., the text inside a paragraph).
Example:

html
Copy
Edit
<p>This is a paragraph.</p>
<h1>This is a heading.</h1>
2. HTML Document Structure
A basic HTML document includes the following mandatory components:

<!DOCTYPE html>: Defines the document type.
<html>: Root element.
<head>: Contains meta-information like the title.
<body>: Contains the visible page content.
Example:

html
Copy
Edit
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a simple web page.</p>
  </body>
</html>
Key HTML Tags
1. Attributes
Attributes provide additional information about elements. They are written within the start tag and typically consist of name-value pairs, e.g., src="image.jpg", href="https://www.example.com".

Common attributes:

href: Specifies the link destination.
src: Defines the path to an image.
style: Sets the inline styles.
class: Assigns a class name for CSS styling.
2. Comments
HTML comments allow you to leave notes in the code that are not visible on the web page. They help with code documentation.

html
Copy
Edit
<!-- This is a comment -->
3. Favicon
A favicon is an icon associated with a website. It appears in the browser tab and bookmarks. Use the <link> tag in the <head> section to add it.

html
Copy
Edit
<head>
  <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
4. Block and Inline Elements
Block-level elements: These take up the full width of their container and start on a new line. Examples: <div>, <p>, <h1>.
Inline elements: These only take up as much space as necessary and do not break the document's flow. Examples: <span>, <a>, <strong>.
5. Class and ID Attributes
Class: Used to apply the same styles to multiple elements.
ID: Uniquely identifies an element.
Example of class and ID usage:

html
Copy
Edit
<div class="container">Content here</div>
<p id="unique-element">This is unique.</p>
HTML Layout Elements
These elements help structure content on a webpage:

<header>: Defines the header for a document or section.
<footer>: Defines the footer for a document or section.
<nav>: Defines navigation links.
<section>: Defines a section in the document.
<article>: Defines a self-contained piece of content.
<aside>: Defines content aside from the main content, like a sidebar.
Semantic vs Non-Semantic HTML
Semantic HTML:
Semantic elements convey meaning about their content, improving accessibility and SEO. Examples: <article>, <section>, <footer>

Non-Semantic HTML:
These elements do not provide any meaning about the content but are used for structure or layout purposes. Examples: <div>, <span>

HTML Style Guide
Indentation: Use consistent indentation (2 or 4 spaces per level).
Element Naming: Use lowercase for tags and hyphenated names for classes/IDs.
Closing Tags: Always close your tags (e.g., <div></div>).
Quotes Around Attributes: Always enclose attribute values in double quotes.
Avoid Inline Styles: Link external CSS files instead of using inline styles.
Whitespace and Line Breaks: Use line breaks between sections for readability.
Comments: Use comments to explain complex sections of the code.
Example:

html
Copy
Edit
<!-- Navigation bar -->
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>
Resources
To further enhance your HTML skills, you can follow this FreeCodeCamp YouTube video.

Happy coding! 🎉
