# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.
- View the optimal layout for the interface depending on their device's screen size.

### Screenshot

![Blog Preview Card Screenshot](./screenshot.png)

_(Tip: Take a screenshot of your completed card, save it in the root folder as `screenshot.png`, or update the path above)_

### Links

- **Solution URL:** [Add your GitHub repository URL here](https://github.com/your-username/blog-preview-card)
- **Live Site URL:** [Add your GitHub Pages / Vercel link here](https://your-username.github.io/blog-preview-card)

---

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties & Flexbox
- [Bootstrap 5](https://getbootstrap.com/) (CDN)
- Custom CSS overrides for pixel-perfect design
- Mobile-first responsive workflow
- [Figtree Font](https://fonts.google.com/specimen/Figtree) via Google Fonts

### What I Learned

In this project, I practiced converting a Figma design into a responsive web component using Bootstrap paired with custom CSS overrides.

Key takeaways:

- Crafting a sharp, unblurred neo-brutalist drop shadow using `box-shadow: 8px 8px 0px 0px #111111;`.
- Combining Bootstrap grid/utility structures with custom micro-spacing to match the Figma spec.
- Managing interactive hover states on accessible anchor tags inside heading elements.

```css
/* Hard shadow matching the design */
.card {
  box-shadow: 8px 8px 0px 0px #111111;
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.card-title a:hover {
  color: #f4d04e;
}
```

### Useful Resources

- [Frontend Mentor Challenge Page](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS) - Design assets, color specifications, and starter files.
- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/components/card/) - Reference for base card structures and utility classes.

---

## Author

- Website - [Mahamud Hasan](https://mahamud-hasan.onrender.com)
- GitHub - [@Mahmud-Hasan2024 ](https://github.com/Mahmud-Hasan2024)
- LinkedIn - [Mahmud Hasan](https://www.linkedin.com/in/mahmud-hasan-2a19892a6/)
