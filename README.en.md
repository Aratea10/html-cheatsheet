# 📝 HTML Cheat Sheet
A quick reference guide with essential HTML elements, their structure, and best practices.

---
<br>

## 🏗️ Basic Structure
| TAG | DESCRIPTION | 
|---|---|
| `<!DOCTYPE html>` | Declaration of HTML5 document type |
| `<html>` | Root element of an HTML document |
| `<head>` | Contains metadata/information for the document | 
| `<body>` | Contains the visible content of the document |
<br>

## 🔤 Text Elements
| TAG | DESCRIPTION |
|------|------------|
| `<h1>` to `<h6>` | Headings (h1 has the highest hierarchy) |
| `<p>`| Paragraph |
| `<strong>`| Bold (strong semantic emphasis) |
| `<em>` | Italic (semantic emphasis) |
| `<br>`| Line break  |
| `<hr>` | Thematic separation (horizontal line) |
| `<blockquote>` | Quote block |
| `<pre>` | Preformatted text (preserves spaces and line breaks) |
| `<code>` | Computer code |
| `<mark>` | Highlighted text |
| `<small>` | Small text (legal notes, etc.) |
| `<sub>` | Subscript text |
| `<sup>` | Superscript text |
<br>

## 🔗 Links and Media
| TAG | DESCRIPTION |
|------|------------|
| `<a href="url">link</a>` | Hypertext link |
| `<img src="image.jpg" alt="DESCRIPCIÓN">` | Image (always include `alt`) |
| `<video src="movie.mp4" controls>` | Video player |
| `<audio src="sound.mp3" controls>` | Audio player |
| `<figure>` | Self-contained content like images, diagrams |
| `<figcaption>` | Description for `<figure>` content |
| `<iframe src="url">` | Inline frame for embedding external content |
| `<source>` | Multiple resources for `<video>` and `<audio>` |
| `<track>` | Subtitles for `<video>` |
<br>

## 📋 Lists
| TAG | DESCRIPTION |
|------|------------|
| `<ul>` | Unordered list (with bullets) |
| `<ol>` | Ordered list (numbered) |
| `<li>` | List item |
| `<dl>` | Definition list |
| `<dt>` | Term in a definition list |
| `<dd>` | Description in a definition list |
<br>

## 🧱 Semantic Structure
| TAG | DESCRIPTION |
|------|------------|
| `<header>` | Introductory content (e.g. logo, navigation) |
| `<nav>` | Navigation links |
| `<main>` | Main content of the document (unique on the page) |
| `<section>` | Thematic grouping of content |
| `<article>` | Self-contained content (e.g. blog post, comment) |
| `<aside>` | Secondary or sidebar content indirectly related |
| `<footer>` | Footer of a section or site |
| `<div>` | Generic container without semantic value |
| `<span>` | Inline container without semantic value |
| `<address>` | Contant information |
| `<details>` | Disclosure control (can be expanded) |
| `<summary>` | Heading for the `<details>` element |
| `<time>` | Specific date and/or time |
<br>

## 📝 Forms
| TAG | DESCRIPTION |
|------|------------|
| `<form>` | Form controls container |
| `<input type="text">` | Text field |
| `<input type="email">` | Email field (with automatic validation) |
| `<input type="password">` | Password field |
| `<input type="checkbox">` | Checkbox |
| `<input type=radio">` | BRadio button |
| `<input type="number">` | Numeric field |
| `<input type="date">` | Date picker |
| `<input type="file">` | File upload |
| `<input type="submit">` | Button to submit the form |
| `<input type="reset">` | Button to reset the form |
| `<textarea>` | Multiline text area |
| `<button>` | Clickable button |
| `<label for="id">` | Label associated with a control (improves accessibility) |
| `<select>` | Dropdown list |
| `<option>` | Option within a `<select>` |
| `<optgroup>` | Group of options in a `<select>` |
| `<fieldset>` | Group of related controls |
| `<legend>` | Title for a `<fieldset>` |
| `<datalist>` | List of options for autocomplete |
| `<output>` | Container for calculation results |
<br>

## 📊 Tables
| TAG | DESCRIPTION |
|------|------------|
| `<table>` | Defines a table |
| `<caption>` | Title or caption for the table |
| `<thead>` | Group of header rows |
| `<tbody>` | Group of body rows |
| `<tfoot>` | Group of footer rows |
| `<tr>` | Table row |
| `<th>` | Header cell |
| `<td>` | Data cell |
| `<colgroup>` | Group of columns |
| `<col>` | Defines properties for columns |

## ⚙️ Elements in `head`
| TAG | DESCRIPTION |
|------|------------|
| `<meta charset="UTF-8">` | Defines the character encoding |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Configures the responsive view |
| `<link rel="stylesheet" href="styles.css">` | Links a CSS stylesheet |
| `<link rel="icon" href="favicon.ico">` | Defines de favicon (page icon) |
| `<title>` | Page title (appears in the browser tab) |
| `<meta name="description" content="...">` | Description for search engines |
| `<meta name="keywords" content="...">` | Keywords (less relevant nowadays) |
| `<meta name="author" content="...">` | Document author |
| `<script src="script.js">` | Links a JavaScript file |
| `<base href="...">` | Base URL for all relative links  |
<br>

## 🔠 Global Attributes
| ATTRIBUTE | DESCRIPTION |
|------|------------|
| `id` | Unique identifier for an element |
| `class` | Class(es) for CSS styles and JavaScript |
| `style` | Inline CSS styles |
| `lang` | Content language |
| `title` | Additional information (tooltip) |
| `hidden` | Hides the element |
| `data-*` | Stores custom data |
| `tabindex` | Tabulation order |
| `accesskey` | Shortcut key |
| `contenteditable` | Allows editing the element's content |
<br>

## 🌐 Obsolete Elements (Avoid)
| TAG | DESCRIPTION |
|------|------------|
| `<center>` | Use CSS: `text-align: center;` instead |
| `<font>` | Use CSS for text styles |
| `<strike>` | Use `<del>` or CSS: `text-decoration: line.through;` |
| `<frameset>`, `<frame>` | Use `<iframe>` if absolutely necessary |
| Attributes like `bgcolor`, `align` | Use CSS for styles |
<br>

## 💡 Best Practices
- Always use semantic elements (`<article>`, `<nav>`, etc.) to improve accessibility and SEO.
- Include the `<alt>` attribute on all images.
- Use lowercase tag and attribute names.
- Properly close tags (in HTML5, `<br>` is valid, but `<br/>` is also accepted).
- Validate your HTML with the [W3C Validator](https://validator.w3.org/).
- Ensure your site is accessible by following WCAG guidelines.
- Use `<button>` for actions and `<a>` for navigation between pages.
- Don't use tables for layout; use them only for tabular data.
- Optimize images before uploading them (appropriate format and size).
- Structure your documents with a clear heading hierarchy (h1, h2, etc).
<br>

## 📚 Glossary
- **Accessibility**: the practice of making websites usable by people with diverse abilities and disabilities.
- **Attribute**: additional information provided in an HTML tag (e.g., href, src, class).
- **CDN**: Content Delivery Network. Network of servers that deliver web content more efficiently.
- **DOM**: Document Object Model. In-memory representation of an HTML document as a tree of nodes.
- **Element**: a part of an HTML page defined by opening and closing tags, or a single tag for empty elements.
- **Favicon**: small icon associated with a website that appears in the browser tab.
- **HTML**: HyperText Markup Language. Standard markup language for creating web pages.
- **Quirks Mode**: rendering mode in browsers when the DOCTYPE declaration is missing or incorrect.
- **Responsive**: design that adapts to different screen sizes and devices.
- **Semantics**: the use of HTML tags that convey meaning about their content, not just about their appearance.
- **SEO**: Search Engine Optimization. Techniques to improve a website's visibility in search engines.
- **Validation**: the process of verifying that an HTML document complies with the rules and standards of the language.
- **Viewport**: visible area of a web page on the device screen.
- **WCAG**: Web Content Accessibility Guidelines. Guidelines for making web content more accessible.

> 💡 **Tip**: for official and updated documentation, visit [MDN Web Docs – HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).
