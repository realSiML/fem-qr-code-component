# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/realSiML/fem-qr-code-component](https://github.com/realSiML/fem-qr-code-component)
- Live Site URL: [https://realsiml.github.io/fem-qr-code-component](https://realsiml.github.io/fem-qr-code-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

By default body has `height: auto`, to center elements inside body, while using grid, we need to give body minimal height like this:

```css
body {
  display: grid;
  place-items: center;
  min-height: 100svh;
}
```

### Continued development

- CSS variables
  - proper naming
  - when to use and when to not
- CSS classes naming.
  - avoid collisions
  - give more semantics

### Useful resources

- [A Modern CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/)

## Author

- Frontend Mentor - [@realSiML](https://www.frontendmentor.io/profile/realSiML)
