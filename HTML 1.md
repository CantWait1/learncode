## Introduction to HTML

### What is HTML?

HTML (HyperText Markup Language) is the standard language for creating web pages. It describes the structure of a webpage using markup.

### Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to HTML!</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```
---

<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to HTML!</h1>
    <p>This is a paragraph.</p>
</body>
</html>

---
- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html>`: Root element of the HTML document.
- `<head>`: Contains meta-information about the document.
- `<title>`: Sets the title of the document (appears in the browser tab).
- `<body>`: Contains the content of the document.


### Text Elements

```html
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<a href="https://www.example.com">This is a link</a>
```
---

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<a href="https://www.example.com">This is a link</a>

---
- `<h1> - <h6>`: Headings, `<h1>` being the highest (most important) and `<h6>` the lowest.
- `<p>`: Paragraph.
- `<a>`: Anchor (link) element, `href` attribute specifies the URL.

### Lists

```html
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
</ul>

<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```
---

<ul>
    <li>List item 1</li>
    <li>List item 2</li>
</ul>

<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>

---
- `<ul>`: Unordered list.
- `<ol>`: Ordered list.
- `<li>`: List item.

### Images

```html
<img src="image.jpg" alt="Description of image">
```
---

<img src="image.jpg" alt="Description of image">

---
- `<img>`: Embeds an image.
- `src`: Specifies the path to the image.
- `alt`: Provides alternative text for the image.

### Tables

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```
---

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>

---
- `<table>`: Defines a table.
- `<tr>`: Table row.
- `<th>`: Table header cell.
- `<td>`: Table data cell.

### Forms

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
```
---

<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>

---
- `<form>`: Defines a form for user input.
- `action`: URL where form data is sent.
- `method`: HTTP method (GET or POST).
- `<label>`: Defines a label for an input element.
- `<input>`: Defines an input field.
- `type`: Specifies the type of input.

### Semantic Elements

```html
<header>
    <h1>Website Header</h1>
</header>
<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>
<main>
    <article>
        <h2>Article Title</h2>
        <p>Article content goes here.</p>
    </article>
</main>
<footer>
    <p>Website Footer</p>
</footer>
```
---

<header>
    <h1>Website Header</h1>
</header>
<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>
<main>
    <article>
        <h2>Article Title</h2>
        <p>Article content goes here.</p>
    </article>
</main>
<footer>
    <p>Website Footer</p>
</footer>

---
- `<header>`: Defines a header for a document or section.
- `<nav>`: Defines a set of navigation links.
- `<main>`: Specifies the main content of a document.
- `<article>`: Defines an article.
- `<footer>`: Defines a footer for a document or section.

### Multimedia Elements

```html
<video controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>
```
---

<video controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>

---
- `<video>`: Embeds a video.
- `<audio>`: Embeds an audio file.
- `<source>`: Specifies multiple media resources.

### Block and Inline Elements

- **Block elements**: Start on a new line and take up the full width (e.g., `<div>`, `<p>`, `<h1>`).
- **Inline elements**: Do not start on a new line and only take up as much width as necessary (e.g., `<span>`, `<a>`, `<img>`).

```html
<div>
    <p>This is a block element.</p>
    <span>This is an inline element inside a block element.</span>
</div>
```
---

<div>
    <p>This is a block element.</p>
    <span>This is an inline element inside a block element.</span>
</div>

---

### Comments

```html
<!-- This is a comment -->
<p>This is a paragraph.</p>
<!-- Comments are not displayed in the browser -->
```
---

<!-- This is a comment -->
<p>This is a paragraph.</p>
<!-- Comments are not displayed in the browser -->

---
`<!-- -->`: Defines a comment.

### Doctype Declaration

```html
<!DOCTYPE html>
```

Specifies the HTML version. For HTML5, use `<!DOCTYPE html>`.