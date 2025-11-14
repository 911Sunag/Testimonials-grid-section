# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

- Mobile view:

![](./screenshots/Screen%20Shot%202025-11-14%20at%2021.25.19.png)

- Desktop view:

![](./screenshots/Screenshot%202025-11-14%20212039.png)

### Links
- Solution URL: [Add solution URL here](https://github.com/911Sunag/Testimonials-grid-section)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.proud-of-this-css {
  @media (max-width: 768px) {

  body {
    padding: 1.5rem;
  }

  main {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: auto;
    gap: 1.5rem;
  }

  .daniel,
  .jonathan,
  .kira,
  .jeanette,
  .patrick {
    grid-column: 1 / 2 !important;
    grid-row: auto !important;
  }

  .clifford,
  .walters,
  .whittle,
  .harmon,
  .abrams {
    align-items: flex-start;
  }
}

@media (min-width: 1440px) {
  body {
    max-width: 1440px;
    margin: 0 auto;
  }
}
}
```
## Author
- Frontend Mentor - [@911Sunag](https://www.frontendmentor.io/profile/911Sunag).