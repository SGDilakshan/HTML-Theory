# HTML-Theory
This repository is your complete guide to HTML, covering everything from core basics to cutting-edge HTML5 features. Whether you're a beginner starting from scratch or a developer refreshing your skills, this is your go-to resource for mastering the structure, semantics, and power of the web.

## 01 - Introduction to HTML  
This is a basic HTML document that displays "Hello world!" on a webpage.  
### Structure:  
- `<DOCTYPE html>` Declares the document as HTML5.  
- `<html>` The root element of the document.  
- `<head>` Contains meta-information, including the title and description.  
- `<title>` Sets the webpage title (shown in the browser tab).  
- `<meta>` Provides a description of the webpage for search engines.  
- `<body>` Contains the visible content of the webpage.  
- `<h1>` Displays the main heading on the page.  

---------------------------------------------------------------------------

## 02 - HTML Tags and Elements Basics  
This HTML file demonstrates basic tags and elements.  
### Key Features:  
- `<h1>` Displays Sivanathan Dilakshan with a red color.  
- `<span>` Used inside the heading for styling purposes.  
- `<p>` Currently empty.  
- `<a>` A clickable link to Google.  
- `<style>` Changes the heading color to red.  

---------------------------------------------------------------------------

## 03 - Formatting Text in HTML  
This HTML file demonstrates basic text formatting tags.  
### Key Features:  
- `<h1>` to `<h6>` Different levels of headings.  
- `<p>` Contains styled text.  
- `<b>` and `<strong>` Highlights important text.  
- `<em>` Emphasized text.  
- `<u>` Underlined text.  
- `<mark>` Highlights text.  
- `<ins>` and `<del>` Shows text modifications.  
- `<sub>` and `<sup>` Displays small text above or below.  
- `<dfn>` Defines a term.  
- `<kbd>` Represents keyboard input.  
- `<pre>` Maintains text formatting.  
- `<time>` Displays a timestamp.  
- `<q>` Adds inline quotes.  

This file showcases various text formatting styles in HTML.  

---------------------------------------------------------------------------

## 04 - Line Breaks and Comments in HTML  
This HTML file demonstrates line breaks and comments in HTML.  
### Key Features:  
- `<!-- -->` Adds comments inside the HTML code.  
- `<p>` Defines a paragraph.  
- `<br>` Inserts a line break within text.  
- `<br/>` Another way to add a line break (self-closing).  
- `<hr>` Creates a horizontal line.  

This file showcases how to use line breaks and comments in HTML.  

---------------------------------------------------------------------------


## 05 - HTML Quotation and Citation Elements  
This HTML file demonstrates quotation and citation tags.  
### Key Features:  
- `<blockquote>` Defines a block of text for a quote, with a citation link.  
- `<abbr>` Represents an abbreviation, with an optional title attribute for full form.  
- `<address>` Represents contact information for the author or owner of the document.  
- `<cite>` Cites a reference or source of the quote.  
- `<bdo>` Controls the text direction (in this example, right-to-left).  

This file showcases how to use various quotation and citation elements in HTML.  

---------------------------------------------------------------------------

## 06_HTML links
This HTML file demonstrates the use of links and the `mailto` feature.
## Key Features:
- **`<a href="new.html">Click here</a>`**: A clickable link that redirects to `new.html`.
- **`<p id="this">Lorem ipsum dolor sit, amet consectetur adipisicing elit...`**: A paragraph with some placeholder text.
- **`<a href="mailto:test@gmail.com">Send mail</a>`**: A link that opens the default mail client to send an email to `test@gmail.com`.

---------------------------------------------------------------------------

# 07_HTML Images
This HTML file demonstrates how to use images and image maps in HTML.  
## Key Features:  
- **`<img>`**: Displays an image with attributes:  
  - `src="./falls-nature.jpg"`: Sets the image source.  
  - `width="300" height="300"`: Defines the image size.  
  - `alt="Fall nature"`: Provides alternative text for accessibility.  
  - `usemap="#map_name"`: Links the image to a map.  

- **`<map name="map_name">`**: Defines an image map with clickable areas.  

- **`<area>`**: Creates clickable areas on the image:  
  - `shape="rect" coords="0,0,100,100"`: Defines a rectangular clickable area linking to [Google](https://google.com).  
  - `shape="circle" coords="150,150,50"`: Defines a circular clickable area linking to [YouTube](https://youtube.com).    

---------------------------------------------------------------------------

# 08_HTML Entities 
This HTML file demonstrates the use of **HTML entities** to display special characters.  
## Key Features:  
- **`&amp;`**: Displays `&` (ampersand).  
- **`&nbsp;`**: Adds a non-breaking space.  
- **`&copy;`**: Displays `©` (copyright symbol).  
- **`&quot;`**: Displays `"` (double quotation mark).  
- **`&lt;h3&gt;`**: Displays `<h3>` as text instead of rendering it as an HTML element.  

This file is useful for displaying reserved characters in HTML without affecting the document structure.  

---------------------------------------------------------------------------

# 09_Generic HTML Elements  
This HTML file demonstrates the use of **generic container elements** in HTML.  
## Key Features:  
- **`<div>`**:  
  - A block-level container used for grouping elements.  
  - Styled with `border: 1px solid black;` to show its boundaries.  

- **`<span>`**:  
  - An inline container used for styling specific portions of text.  
  - Styled with `border: 1px solid black;` to show its boundaries.  

This file highlights the difference between **block-level (`<div>`)** and **inline (`<span>`)** elements in HTML.  

---------------------------------------------------------------------------

# 10_HTML Lists
This HTML file demonstrates different types of lists in HTML, including unordered lists, ordered lists, nested lists, description lists, and list items with links.  
## Key Features:  
- **`<ul>` (Unordered List)**  
  - Displays a bulleted list.  
  - Example: Days of the week in an unordered list.  

- **`<ol>` (Ordered List)**  
  - Displays a numbered list.  
  - Example: Days of the week in an ordered list.  
  - Supports attributes like `type="I"` and `start="10"`.  

- **Nested Lists**  
  - Unordered list inside another unordered list.  
  - Ordered list inside another ordered list.  

- **List Items with Links**  
  - `<a href="https://www.google.com" target="_blank">`: Opens a link in a new tab.  

- **`<dl>` (Description List)**  
  - `<dt>` (Definition Term): Represents the term.  
  - `<dd>` (Definition Description): Provides the definition.  

This file showcases various ways to structure and format lists in HTML.  

---------------------------------------------------------------------------