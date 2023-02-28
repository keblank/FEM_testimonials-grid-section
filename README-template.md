# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 3rem;
  grid-template-areas:
    "box1 box1 box2 box5"
    "box3 box4 box4 box5";
}

.box1 {
  grid-area: box1;
  background-image: url(./images/bg-pattern-quotation.svg);
  background-repeat: no-repeat;
  background-position-x: 90%;
}
```

### Continued development

- Use of css grid
- streamline css

## Author

- Kells
- Frontend Mentor - [@keblank](https://www.frontendmentor.io/profile/keblank)
