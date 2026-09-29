# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO_2334766_M). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements (such as the "Add to Cart" button)

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/seyyidalirebouhi-a11y/product-preview-card-component)
- Live Site URL: [Live Site](https://seyyidalirebouhi-a11y.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- Responsive design with `@media` queries
- `<picture>` element for art-direction image switching
- Google Fonts (`Montserrat`, `Figtree`)

### What I learned

In this challenge, I practiced building a product preview card and implementing responsive media techniques. I used the `<picture>` element in HTML to automatically switch between mobile and desktop product images based on screen width:

```html
<picture class="recipe-image">
  <source media="(max-width: 900px)" srcset="./images/image-product-mobile.jpg">
  <img src="./images/image-product-desktop.jpg" alt="Gabrielle Essence Eau De Parfum">
</picture>