# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/AhmedHussien249/qr-code-component)
- Live Site URL: [Live Demo on Vercel](https://qr-code-component1-nine.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties & HSL color values
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I focused on building a clean and responsive component using semantic HTML5 and CSS Flexbox:

- **Semantic HTML**: Structuring content using `<main>` and `<article>` tags for proper document hierarchy and accessibility.
- **Centering with Flexbox**: Aligning the component seamlessly in the center of the viewport using `display: flex`, `align-items: center`, `justify-content: center`, and `min-height: 100vh`.
- **Responsive Layout**: Using `max-width: 90vw` to maintain flexibility on smaller screens without overflowing.

```html
<main>
  <article>
    <img src="assets/image-qr-code.png" alt="QR code linking to Frontend Mentor">
    <h1 class="title">Improve your front-end skills by building projects</h1>
    <p class="description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </article>
</main>
