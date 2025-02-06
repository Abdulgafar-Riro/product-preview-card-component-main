# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product Preview Card Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product Preview Card](./screenshots/desktop-view.png)
![Product Preview Card](./screenshots/mobile-view.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Abdulgafar-Riro/product-preview-card-component-main/tree/branches-4)
- Live Site URL: [Live Demo]([https://your-live-site-url.com](https://webmujahid-product-preview-card.netlify.app/))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project helped reinforce my understanding of **responsive design** and **CSS Flexbox**. The `<picture>` element was particularly useful for handling responsive images:

```html
<picture>
  <source media="(min-width: 35rem)" srcset="./images/image-product-desktop.jpg">
  <img src="./images/image-product-mobile.jpg" alt="Product image">
</picture>

For styling buttons, I used hover and cursor properties to enhance interactivity:

button:hover {
  background-color: var(--Very-dark-blue);
  cursor: pointer;
}

Continued development

In future projects, I plan to:

Explore CSS Grid for complex layouts

Improve ARIA accessibility for better screen reader support

Experiment with JavaScript to add interactivity


Useful resources

CSS Tricks - A Complete Guide to Flexbox - Helped with layout structuring.

MDN Web Docs - Picture Element - Assisted in implementing responsive images.


Author

GitHub - Abdulgafar-Riro

Frontend Mentor - @Abdulgafar-Riro



---

This project is part of my Frontend Mentor learning journey. Feedback and suggestions are welcome!
