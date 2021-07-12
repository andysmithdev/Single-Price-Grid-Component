# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/andysmithdev/Single-Price-Grid-Component](https://github.com/andysmithdev/Single-Price-Grid-Component)
- Live Site URL: [https://andysmithdev.github.io/Single-Price-Grid-Component/](https://andysmithdev.github.io/Single-Price-Grid-Component/)

## My process

### Built with

- CSS

### What I learned

The hardest part for me was vertically centering the 'per month' text. It took a while to release that you needed to add the 'vertical-align: middle;' property to the 'price' span rather than the 'per month' span. No idea why this is, makes no sense.

```css
.price {
    font-size: 32px;
    font-weight: 700;
    vertical-align: middle; /* No idea why this needs to be here to align .permonth correctly */
    line-height: normal;
}
```

## Author

- Frontend Mentor - [@andysmithdev](https://www.frontendmentor.io/profile/andysmithdev)

