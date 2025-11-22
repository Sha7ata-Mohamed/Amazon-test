# A Basic Introduction to HTML

## What is HTML?

HTML stands for **HyperText Markup Language**. It's the standard markup language for creating web pages and web applications. Think of it as the skeleton of a webpage; it provides the basic structure and content.

- **HyperText:** Refers to the "links" that connect web pages to one another, allowing the user to click their way from page to page.
- **Markup Language:** Means that HTML uses "tags" to "mark up" or describe the content. The browser then knows how to display that content.

---

## Basic Structure of an HTML Document

Every HTML document has a common structure that looks like this:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>

    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>

</body>
</html>
```

### Explanation of Tags:

-   `<!DOCTYPE html>`: Declares that this document is an HTML5 document.
-   `<html>`: The root element of an HTML page. All other elements go inside of this.
-   `<head>`: Contains meta-information about the HTML page, such as the title. This content is not displayed on the page itself.
-   `<title>`: Specifies a title for the HTML page, which is shown in the browser's title bar or in the page's tab.
-   `<body>`: Contains the visible page content that is displayed in the browser.

---

## Common HTML Tags

Here are a few of the most common tags you'll encounter:

| Tag           | Description                                  |
|---------------|----------------------------------------------|
| `<h1>` to `<h6>` | Headings. `<h1>` is the most important.      |
| `<p>`         | A paragraph of text.                         |
| `<a>`         | An anchor tag, used to create a hyperlink.   |
| `<img>`       | An image tag, used to embed an image.        |
| `<div>`       | A division or a section in a document.       |
| `<span>`      | An inline container for text or documents.   |
| `<ul>`, `<ol>`, `<li>` | Used to create unordered and ordered lists. |
| `<b>`, `<strong>` | Make text bold. `<strong>` has semantic importance. |
| `<i>`, `<em>`   | Make text italic. `<em>` has semantic importance. |

### Example with more tags:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
</head>
<body>

    <h1>Welcome to My Website!</h1>
    <p>This is a paragraph about my website. You can find useful links and images below.</p>

    <h2>Useful Links</h2>
    <ul>
        <li><a href="https://www.google.com">Go to Google</a></li>
        <li><a href="https://www.wikipedia.org">Go to Wikipedia</a></li>
    </ul>

    <h2>A Picture</h2>
    <img src="https://via.placeholder.com/150" alt="A placeholder image">

</body>
</html>
```
