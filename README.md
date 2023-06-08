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


## HTML Page Structure
<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/html_structure.jpg" alt="HTML page structure" height="500" width="500">

# CSS(Cascading Style Sheets)

## Style Text
Important properties to style text with CSS:
```css
    font-size: 26px;
    font-family: sans-serif;
    text-transform: uppercase;
    font-style: italic;
    line-height: 1.5; /* (unit) */
    text-align: center;
    font-weight: bold;
    text-decoration: underline;
```

## HTML Selector
### ID Selector:
```html
   <div id="myElement">...</div>
```
```css
#myElement {
  /* CSS styles */
}
```

### Class Selector:
```html
<div class="myCass">...</div>
```

```css
.myClass {
  /* CSS styles */
}
```
## Difference between ID and Class selector.
### ID Selector:
- An ID selector is used to uniquely identify an element on a web page. It should be unique within the entire HTML document. You can assign an ID to any HTML element using the id attribute. ID selectors are denoted by the hash symbol (#) followed by the ID value.
- Unique: IDs must be unique within the HTML document.
- High specificity: ID selectors have higher specificity than class selectors, which means they override styles applied by class selectors.
- Used for individual elements: IDs are often used to style or manipulate a specific element on a page.

### Class Selector:
- A class selector is used to select multiple elements that share the same class attribute. You can assign a class to any HTML element using the class attribute. Class selectors are denoted by a dot (.) followed by the class name. 
- Not unique: Multiple elements can share the same class.
- Lower specificity: Class selectors have lower specificity than ID selectors, so styles applied by ID selectors override those applied by class selectors.
- Used for multiple elements: Classes are often used to apply common styles or functionality to multiple elements throughout a page.


# Color
### RGB Color:
RDB color is a way of representing colors using three primary color channels: `red`, `green`, and `blue`. Each channel is typically represented by an integer value ranging from `0` to `255`, indicating the intensity of that color channel. By combining different intensities of red, green, and blue, a wide range of colors can be created. For example, RDB color code rgb(255, 0, 0) represents pure red, while rgb(0, 255, 0) represents pure green.

### Hexadecimal Color:
Hexadecimal color codes, often referred to as hex codes, are a way of representing colors using a combination of six hexadecimal digits. Each digit represents an intensity level of one of the three primary color channels: `red`, `green`, and `blue`. Hexadecimal digits range from `0` to `9` and `A` to `F`, where A represents 10, B represents 11, and so on, up to F representing 15.They are denoted by a hash symbol (#) followed by six hexadecimal digits. For example, #FF0000 represents pure red, and #00FF00 represents pure green.

**Note**:
- We all the time use Hex color but when we need `opacity` then use opacity then use `RGBA(Red-Green-Blue-Alpha)`. The alpha value represents transparency, with 0 meaning fully transparent and 1 meaning fully opaque. Where the alpha value is set to 0.5 (50% opacity).


# CSS Box Model
The box model is one of the most fundamental and important principles of CSS so we will spend a decent amount of time on this and create several examples. Every HTML element hava it's own default box model.
- `Content` – The text, image, input or whatever the actual content is inside the box.
- `Padding` – The space between the content and the border on all four sides.
- `Border` – Just what it sounds like. This is where the styling for the box ends.
- `Margin` – The space between the box and the other objects around it.

<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/boxmodel.png" alt="HTML element" height="150" width="500">

**Note:**

- Whenever you need some space inside of an element, use `Peding`.
- Whenever you need some space outside of an element, use `Margin`.


# Type of Boxes in CSS

### Block-level boxes:
- Block-level boxes are the default type of box for most HTML elements, such as `<div>, <p>, and <h1> to <h6>`.
- They take up the entire width of their parent container by default and stack vertically one after another.
- You can control their dimensions (width and height) and apply margins, padding, and borders to them.

<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/block_boxes.png" alt="HTML element" height="350" width="400">

### Inline-block boxes:
- Inline boxes are used for elements that are naturally inline, such as `<span>, <a>, <strong>, <img>, <em>, <button> etc`.
- They don't break the flow of text and typically occupy only the space required by their content.
- Inline boxes ignore width, height, and top/bottom margins but can have left/right margins, padding, and borders.
