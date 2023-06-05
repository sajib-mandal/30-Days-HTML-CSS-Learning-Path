# HTML
<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/html_element.png" alt="HTML element" height="200" width="400">

## What is Non-Semantice HTML?
Non-semantic HTML elements are those that don't provide inherent meaning or context to the content they contain. These elements are primarily used for presentational purposes and don't convey the structure or purpose of the content. Tells nothing about its content. While these non-semantic elements can still be used in HTML, it is generally recommended to prioritize the use of semantic elements whenever possible. Semantic elements provide better structure, accessibility, and search engine optimization (SEO) benefits, as they convey meaning and improve the overall understanding of the content. Here are some examples of non-semantic HTML elements along with their common meanings:

- `<div>`: A generic container used to group and style content. It doesn't have any specific meaning or semantic value.

- `<span>`: A generic inline container used for applying styles or scripting to small portions of text.

- `<b>`: Represents bold text. It is often used for visual styling, but it doesn't convey any semantic meaning.

- `<i>`: Represents italicized text. Similarly, it is primarily used for styling rather than conveying specific meaning.

- `<u>`: Represents underlined text. It is also used for visual styling purposes rather than indicating specific meaning.

- `<font>`: Used to apply font styles, sizes, and colors to text. However, it is considered outdated and is no longer recommended for use.

- `<center>`: Used to horizontally center-align content within a container. Like `<font>`, it is considered outdated and should be avoided.

- `<br>`: Represents a line break, used to create a new line within a paragraph or block of text.

- `<hr>`: Represents a horizontal rule or divider, used to separate content sections.

- `<s>`: Represents strikethrough text. It is commonly used to indicate deleted or deprecated content.

- `<small>`: Renders the enclosed text in a smaller font size. It is typically used for disclaimers or fine print.

- `<sup>`: Renders the enclosed text as superscript, typically used for footnotes or mathematical exponents.

- `<sub>`: Renders the enclosed text as subscript, often used for chemical formulas or mathematical subscripts.

## What is Semantice HTML?
Semantic HTML (also called semantic markup) is HTML code that uses HTML tages to effectively describe the purpose of page elements. Semantic HTML code communicates the meaning of it's elements to both computers and humans, which helps web browsers, search engines, assistive technologies, and human developers understand the components of a web page.

Semantic HTML elements provide meaning and structure to the content within an HTML document. They convey information about the purpose and role of different sections or elements on a webpage. Here are some commonly used semantic HTML elements along with their meanings:

- **`<strong>`**: Represents strong importance or emphasis. Draws attentaion to important text. Most browsers BOLD the text inside this tag by default.
- **`<em>`**: Represents emphasized text. Most browsers ITALICIZE text inside this tag by default.
- **`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`**: Heading elements represent hierarchical levels of section headings, with `<h1>` being the highest and `<h6>` being the lowest.
- **`<p>`**: Represents a paragraph of text.
- **`<ol>`**: Represents ordered list.
- **`<ul>`**: Represents unordered list.
- **`<a>`**: Represents anchor. A hyperling. By default, browsers will change the link color to blue and add a `underline which you can remove`.
- **`<button>`**: A button element.
- **`<img>`**: An image.
- **`<table>`**: A table with columns and rows of data.
- **`<header>`**: Represents the introductory content or the header section of a document or a section within a document.
- **`<header>`**: Represents the introductory content or the header section of a document or a section within a document.
- **`<nav>`**: Represents a section of navigation links.
- **`<main>`**: Represents the main content area of a document. It should be unique and not repeated across multiple pages.
- **`<article>`**: Represents a self-contained composition, such as a blog post, article, or a news story.
- **`<section>`**: Represents a standalone section within a document that groups related content.
- **`<aside>`**: Represents content that is tangentially related to the main content, often displayed as a sidebar.
- **`<footer>`**: Represents the footer section of a document or a section within a document, typically containing authorship information, copyright notices, or related links.
- **`<figure> and <figcaption>`**: Used for images that require a description. `<figure>` contains the image itself, and `<figcaption>` contains the caption associated with the image.
- **`<figcaption>`**: Represents the caption or description for a `<figure>` element.
- **`<q> (quote) and <blockquote>`**: A quotation. Use `<q>` for shorter quotes and `<blockquote>` for longer quotes.
- **`<cite>`**: Represents the title or source of a work, such as the name of a book or the author of an article.
- **`<time>`**: Represents a specific time or a range of time.
- **`<mark>`**: Represents highlighted or marked text for reference or emphasis.
- **`<abbr>`**: Represents an abbreviation or acronym, providing additional information or expanding the abbreviated term.
- **`<code>`**: Represents a fragment of computer code or a code sample.
- **`<pre>`**: Represents preformatted text, typically used for displaying code blocks or preserving whitespace formatting.


## How to Bold Text in HTML?
To bold the text in HTML, you can use either the `<strong>` tag or the `<b>` (bold) tag. Browsers will bold the text inside both of these tags the same way, but the `<strong>` tag indicates that the text is of particular importance. You can also bold text with the CSS `font-weight` property set to `bold`.

When bolding text, it’s considered a best practice to use the `<strong>` tag. This is because it is `semantic element`, whereas `<b>` is not. Non-semantic elements are worse for accessibility and can make content localization and future-proofing difficult. Additionally, if the text bolding is purely stylistic, it’s better to use CSS and keep all page styling separate from the content.

```html
<p>HTML stands for <strong>Hypertext Markup Language</strong></p>
```
