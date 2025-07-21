# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Responsive design](#responsive-design)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Preview Screenshot](./img/preview.jpg)

### Links

- Solution URL: [GitHub Repo](https://github.com/MATBMS/bento-grid)
- Live Site URL: [Live Site](https://matbms-bento-grid.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how to let an image extend beyond its container by adjusting CSS properties such as `overflow`, `object-fit`, and setting fixed dimensions. This approach helps achieve specific visual effects and ensures the image displays as intended within flexible layouts.

```css
#schedule {
  gap: 24px;
  padding: 32px;
  overflow: hidden;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

#schedule img {
  min-width: 357px;
  width: 357px;
  height: 318px;
  flex-shrink: 0;
  object-fit: contain;
}
```

### Responsive Design

The site is responsive, with layouts for mobile and tablet devices at the following breakpoints:

```css
/* TABLET */

@media (max-width: 768px) {
}

/* MOBILE */

@media (max-width: 375px) {
}
```
