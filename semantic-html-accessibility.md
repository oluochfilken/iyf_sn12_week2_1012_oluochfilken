# Semantic HTML and Accessibility

**Author:** Oluoch Filken  
**Course:** IYF Weekend Academy Season 12  
**Topic:** Semantic HTML and Web Accessibility

## Introduction

Semantic HTML means using HTML elements according to their meaning and purpose.

Examples include:

- `<header>` for introductory content.
- `<nav>` for navigation links.
- `<main>` for the main content.
- `<article>` for independent content.
- `<section>` for related content.
- `<aside>` for supporting content.
- `<footer>` for footer information.

## Why Semantic HTML Is Important

1. It improves website accessibility.
2. It makes HTML easier to read and maintain.
3. It helps screen readers understand page structure.
4. It helps browsers interpret page content.

## Accessibility Best Practices

### 1. Use Image Alternative Text

Images should have meaningful alt text when they communicate information.

Example:

`<img src="photo.jpg" alt="Developer working at a computer">`

Decorative images can use an empty alt attribute.

### 2. Label Form Inputs

Every form input should have an associated label.

Example:

`<label for="email">Email Address</label>`

`<input type="email" id="email" name="email">`

### 3. Use Headings Correctly

Use headings in a logical hierarchy, starting with an appropriate `<h1>`.

### 4. Support Keyboard Navigation

Users should be able to navigate links and controls using a keyboard.

### 5. Use Sufficient Colour Contrast

Text and backgrounds should have sufficient contrast to remain readable.

## Semantic HTML Example

```html
<header>
  <h1>My Website</h1>
  <nav>
    <a href="index.html">Home</a>
  </nav>
</header>

<main>
  <article>
    <h2>About Web Development</h2>
    <p>Web development involves creating websites.</p>
  </article>
</main>

<footer>
  <p>Copyright 2026</p>
</footer>