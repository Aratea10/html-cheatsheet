# 📝 HTML Cheatsheet

A quick reference guide to essential HTML elements, structure, and best practices.

---

## 🔤 Text Elements
| TAG | DESCRIPTION |
|------|------------|
| `<h1> to <h6>` | Headings (h1 is highest level) |
| `<p>`| Paragraph |
| `<strong>`| Bold (semantic importance) |
| `<em>` | Italic (semantic emphasis) |
| `<br>`| Line break |
| `<hr>` | Thematic break (horizontal rule) |

## 🔗 Links & Media
| TAG | DESCRIPTION |
|------|------------|
| `<a href="url">link</a>` | Hyperlink |
| `<img src="image.jpg" alt="description">` | Image (always include `alt`) |
| `<video src="movie.mp4" controls>` | Video player |
| `<audio src="sound.mp3" controls>` | Audio player |

## 📋 Lists
| TAG | DESCRIPTION |
|------|------------|
| `<ul>` | Unordered (bulleted) list |
| `<ol>` | Ordered (numbered) list |
| `<li>` | List item |

## 🧱 Semantic Layout
| TAG | DESCRIPTION |
|------|------------|
| `<header>` | Introductory content (e.g., logo, navigation) |
| `<nav>` | Navigation links |
| `<main>` | Primary content of the document |
| `<section>` | Thematic grouping of content |
| `<article>` | Self-contained composition (e.g., blog post) |
| `<aside>` | Sidebar or tangential content |
| `<footer>` | Footer for a section or page |

## 📝 Forms
| TAG | DESCRIPTION |
|------|------------|
| `<form>` | Container for form controls |
| `<input type="text">` | Text input |
| `<input type="email">` | Email input (with validation) |
| `<input type="password">` | Password field |
| `<input type="checkbox">` | Checkbox |
| `<input type="radio">` | Radio button |
| `<textarea>` | Multi-line text input |
| `<button>` | Clickable button |
| `<label for="id">` | Label for a form control (improves accessibility) |

## ⚙️ Meta & Head Elements
| TAG | DESCRIPTION |
|------|------------|
| `<meta charset="UTF-8">` | Specifies character encoding |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Responsive viewport |
| `link rel="stylesheet" href="styles.css">` | Link to external CSS |
| `<title>` | Page title (shown in browser tab) |

## 💡 Best Practices
- Always use semantic HTML elements (`<article>`, `<nav>`, etc.) for better accessibility and SEO.
- Include `<alt>` attributes for all images.
- Use lowercase tag and attribute names.
- Close all tagas properly (e.g., `<br/>`is optional in HTML5, but self-closing is fine).
- Validate your HTML with the [W3C Validator](https://validator.w3.org/).

> 💡 **Tip**: For official documentation, visit [MDN Web Docs – HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).