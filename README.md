# HTML
<img src="https://github.com/sajib-mandal/30-Days-HTML-CSS-Learning-Path/blob/main/images/html_element.png" alt="HTML element" height="200" width="400">

## What is Semantice HTML?

Semantic HTML (also called semantic markup) is HTML code that uses HTML tages to effectively describe the purpose of page elements. Semantic HTML code communicates the meaning of it's elements to both computers and humans, which helps web browsers, search engines, assistive technologies, and human developers understand the components of a web page.

- **`<header>`**: Represents the introductory content or the header section of a document or a section within a document.


## How to Bold Text in HTML?
To bold the text in HTML, you can use either the `<strong>` tag or the `<b>` (bold) tag. Browsers will bold the text inside both of these tags the same way, but the `<strong>` tag indicates that the text is of particular importance. You can also bold text with the CSS `font-weight` property set to `bold`.

When bolding text, it’s considered a best practice to use the `<strong>` tag. This is because it is `semantic element`, whereas `<b>` is not. Non-semantic elements are worse for accessibility and can make content localization and future-proofing difficult. Additionally, if the text bolding is purely stylistic, it’s better to use CSS and keep all page styling separate from the content.

```html
<p>HTML stands for <strong>Hypertext Markup Language</strong></p>
```
