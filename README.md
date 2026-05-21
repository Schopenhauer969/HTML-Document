# 🌐 HTML Complete Guide — Beginner to Advanced

HTML = HyperText Markup Language  
Used to structure websites and web applications.

---

# 📄 Basic HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
</head>
<body>

  <h1>Hello World</h1>
  <p>My first website.</p>

</body>
</html>
```

---

# 🧠 HTML Structure

| Tag | Purpose |
|------|----------|
| `<!DOCTYPE html>` | HTML5 document |
| `<html>` | Root element |
| `<head>` | Metadata |
| `<body>` | Website content |

---

# 🏷️ Headings

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Heading</h3>
<h4>Heading</h4>
<h5>Heading</h5>
<h6>Smallest Heading</h6>
```

---

# ✍️ Text Formatting

```html
<b>Bold</b>
<strong>Important</strong>

<i>Italic</i>
<em>Emphasis</em>

<u>Underline</u>

<mark>Highlight</mark>

<small>Small Text</small>

<del>Deleted</del>

<sub>Subscript</sub>
<sup>Superscript</sup>
```

---

# 🔗 Links

```html
<a href="https://google.com">Google</a>

<a href="about.html">About</a>

<a href="#section">Go Section</a>

<a href="mailto:test@gmail.com">Email</a>
```

---

# 🖼️ Images

```html
<img src="image.jpg" alt="Nature" width="300">
```

## Responsive Image

```html
<img src="image.jpg" alt="" style="max-width:100%;">
```

---

# 📋 Lists

## Unordered List

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

## Ordered List

```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

## Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>Markup Language</dd>
</dl>
```

---

# 📦 Containers

## Div

```html
<div>Block Element</div>
```

## Span

```html
<span>Inline Element</span>
```

---

# 🧱 Semantic HTML

```html
<header></header>
<nav></nav>
<main></main>
<section></section>
<article></article>
<aside></aside>
<footer></footer>
```

✅ Better SEO  
✅ Better Accessibility  
✅ Cleaner Structure

---

# 📥 Forms

```html
<form>

  <label>Username</label>
  <input type="text">

  <label>Password</label>
  <input type="password">

  <button type="submit">
    Login
  </button>

</form>
```

---

# ☑️ Input Types

```html
<input type="text">
<input type="email">
<input type="password">
<input type="number">
<input type="date">
<input type="file">
<input type="checkbox">
<input type="radio">
<input type="range">
<input type="color">
```

---

# ✅ Form Validation

```html
<input
  type="email"
  required
  minlength="5"
  maxlength="30"
>
```

---

# 📊 Tables

```html
<table border="1">

  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>John</td>
      <td>20</td>
    </tr>
  </tbody>

</table>
```

---

# 🎵 Audio

```html
<audio controls>
  <source src="music.mp3">
</audio>
```

---

# 🎬 Video

```html
<video controls width="400">
  <source src="video.mp4">
</video>
```

---

# 🧩 Iframe

```html
<iframe
  src="https://example.com"
  width="500"
  height="300">
</iframe>
```

---

# 📌 Buttons

```html
<button>Click</button>
```

---

# 🎨 Add CSS

```html
<link rel="stylesheet" href="style.css">
```

---

# ⚡ Add JavaScript

```html
<script src="script.js"></script>
```

---

# 📱 Responsive Meta Tag

```html
<meta
  name="viewport"
  content="width=device-width, initial-scale=1.0">
```

---

# 🌍 SEO Meta Tags

```html
<meta name="description" content="My website">

<meta name="keywords" content="HTML,CSS,JavaScript">

<meta name="author" content="Your Name">
```

---

# 🚀 Open Graph Meta Tags

```html
<meta property="og:title" content="My Website">

<meta property="og:description" content="Awesome site">

<meta property="og:image" content="image.jpg">
```

---

# ♿ Accessibility

```html
<img src="cat.jpg" alt="Cute Cat">

<button aria-label="Close Menu">
  X
</button>
```

---

# 🧠 HTML Entities

```html
&lt;   Less Than
&gt;   Greater Than
&amp;  Ampersand
&nbsp; Space
```

---

# 📂 File Paths

## Relative Path

```html
<img src="./images/photo.jpg">
```

## Absolute Path

```html
<img src="/images/photo.jpg">
```

---

# 🛠️ Advanced Semantic Layout

```html
<body>

  <header></header>

  <nav></nav>

  <main>

    <section>
      <article></article>
    </section>

    <aside></aside>

  </main>

  <footer></footer>

</body>
```

---

# ⚙️ Data Attributes

```html
<div data-id="101">
  Product
</div>
```

---

# 🧲 Lazy Loading

```html
<img
  src="image.jpg"
  loading="lazy"
  alt="">
```

---

# 📡 HTML APIs

## Geolocation

```html
navigator.geolocation.getCurrentPosition();
```

## Drag & Drop

```html
draggable="true"
```

---

# 🧪 Canvas

```html
<canvas id="game"></canvas>
```

---

# 🌐 SVG

```html
<svg width="100" height="100">

  <circle
    cx="50"
    cy="50"
    r="40"
  />

</svg>
```

---

# 🔥 Best Practices

✅ Use semantic tags  
✅ Use alt text  
✅ Keep indentation clean  
✅ Use lowercase tags  
✅ Optimize images  
✅ Validate forms  
✅ Keep accessibility in mind

---

# 📁 Recommended Project Structure

```text
project/
│
├── index.html
├── pages/
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
└── assets/
```

---

# 🛠️ VS Code Extensions

- Live Server
- Prettier
- Auto Rename Tag
- HTML CSS Support
- IntelliSense

---

# 📚 Next To Learn

1. HTML
2. CSS
3. Flexbox
4. Grid
5. JavaScript
6. DOM
7. React
8. APIs

---

# ❤️ Made For Developers
