# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop Screenshot](./desktop-screenshot.jpg)
![Tablet Screenshot](./tablet-screenshot.jpg)
![Mobile Screenshot](./mobile-screenshot.jpg)

### Links

- Solution URL: [https://github.com/ChechiX/testimonials-grid-section](https://github.com/ChechiX/testimonials-grid-section)
- Live Site URL: [https://chechix.github.io/testimonials-grid-section/](https://chechix.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- Sass variables and inheritance
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use grid to create columns and to position the content.

```scss
grid-template-columns: repeat(4, 1fr);

.daniel__section {
  grid-column: 1 / 3;
}

.patrick__section {
  grid-row: 2 / 3;
  grid-column: 2 / 4;
}

.kira__section {
  grid-row: 1 / 3;
  grid-column: 4 / 5;
}
```

### Continued development

I want to continue learning more about grid systems because it took me longer than expected to solve the challenge.

### Useful resources

- [CSS Grid Garden](https://cssgridgarden.com/) - This helped me understand the "shortcuts" available in grid when positioning grid elements.

## Author

- Frontend Mentor - [@ChechiX](https://www.frontendmentor.io/profile/ChechiX)
