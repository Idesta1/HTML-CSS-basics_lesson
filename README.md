# HTML-CSS-basics_lesson


## Overview
This lesson introduces the fundamental building blocks of web development: HTML and CSS. Students will learn how to create and style a simple web page.

---

## Objectives
- Understand what HTML and CSS are
- Write basic HTML to structure a web page
- Apply CSS to style HTML elements
- Build a simple, styled web page

---

## 1. Introduction to HTML

### What is HTML?
- HTML stands for **HyperText Markup Language**
- It is used to create the structure and content of web pages

### Basic HTML Structure
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Page content goes here -->
  </body>
</html>
```

### Common HTML Tags
- Headings: `<h1>`, `<h2>`, ..., `<h6>`
- Paragraph: `<p>`
- Link: `<a href="https://example.com">Link</a>`
- Image: `<img src="image.jpg" alt="Description">`
- List: `<ul>`, `<ol>`, `<li>`

---

## 2. Introduction to CSS

### What is CSS?
- CSS stands for **Cascading Style Sheets**
- CSS is used to style and layout web pages

### Ways to Add CSS
- **Inline**: Using the `style` attribute  
  Example: `<p style="color:red;">Red text</p>`
- **Internal**: Using a `<style>` tag in the `<head>`
- **External**: Linking a `.css` file

### Example (Internal CSS)
```html
<head>
  <style>
    body { background-color: #f0f0f0; }
    h1 { color: blue; }
    p { font-size: 18px; }
  </style>
</head>
```

---

## 3. Hands-On Activity

### Task
Create a simple web page that includes:
- A heading (`<h1>`)
- A paragraph (`<p>`)
- A link (`<a>`)
- Basic CSS styling (colors, fonts)

### Example Solution
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
    <style>
      body { background-color: #fffbe7; }
      h1 { color: #3a3aee; }
      p { font-family: Arial, sans-serif; }
      a { color: #f26b38; }
    </style>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML and CSS page.</p>
    <a href="https://www.example.com">Visit Example</a>
  </body>
</html>
```

---

## 4. Review & Discussion

- What does HTML do? What does CSS do?
- How would you make a heading red?
- How do you add a link to another website?

---

## 5. Further Practice

- Add an image to your page
- Create an unordered list of your favorite foods
- Change the background color of your page

---

## Resources

- [MDN Web Docs: HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [MDN Web Docs: CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

---