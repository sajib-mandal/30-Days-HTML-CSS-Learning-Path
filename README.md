# HTML
<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/html_element.png" alt="HTML element" height="200" width="400">

## What is Semantice HTML?
Semantic HTML (also called semantic markup) is HTML code that uses HTML tages to effectively describe the purpose of page elements. Semantic HTML code communicates the meaning of it's elements to both computers and humans, which helps web browsers, search engines, assistive technologies, and human developers understand the components of a web page.

- **`<header>`**: Represents the introductory content or the header section of a document or a section within a document.
Semantic HTML elements provide meaning and structure to the content within an HTML document. They convey information about the purpose and role of different sections or elements on a webpage. Here are some commonly used semantic HTML elements along with their meanings:

- **`<strong>`**: Represents strong importance or emphasis. Draws attentaion to important text. Most browsers BOLD the text inside this tag by default.
- **`<em>`**: Represents emphasized text. Most browsers ITALICIZE text inside this tag by default.
- **`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`**: Heading elements represent hierarchical levels of section headings, with `<h1>` being the highest and `<h6>` being the lowest.
- **`<p>`**: Represents a paragraph of text.

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
