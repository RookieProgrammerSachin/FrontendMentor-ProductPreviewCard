# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
Completed the challenge successfully while resembling the designs as close as possible.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries for responsiveness
- Sass CSS compiler

### What I learned

In order to change the image displayed based on the device in which the site is viewed, I used two images with `display:block;` for the image with `.product-mobile` class and `display:none` for the image with class `.product` in the media query and vice-versa outside the query.

```css
@media (max-width: 650px) {
  .product {
    display: none;
  }
  .product-mobile {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 10px 10px 0 0;
    filter: brightness(90%) contrast(110%);
  }
}
```

### Useful resources

- [Sass compiler](https://sass-lang.com) - This helped me write CSS in an easier and more modular way with better variable declaration

## Author

- Website - [RookieProgrammerSachin](https://github.com/RookieProgrammerSachin)
- Frontend Mentor - [@RookieProgrammerSachin](https://www.frontendmentor.io/profile/RookieProgrammerSachin)

## Acknowledgments

This [YouTube video](https://www.youtube.com/watch?v=lAOkx2yZESY) helped get things started with RWD with the help of media queries.
