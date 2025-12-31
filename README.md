# Frontend Mentor - Digitalbank landing page solution

This is a solution to the [Digitalbank landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/digital-bank-landing-page-WaUhkoDN). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Add your screenshot: `./screenshot.jpg` (capture in your browser and drop it in the repo).

### Links

- Solution URL: _Add solution URL here_
- Live Site URL: _Add live site URL here_

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla JavaScript for navigation, modal, FAQ, and validation

### What I learned

Key takeaways:

- Building a responsive hero with layered `picture` + positioned mockups for art direction.
- Managing mobile navigation with an accessible focus trap and scroll locking.
- Structuring FAQ, testimonials, and pricing cards with reusable grid patterns.
- Toggling themes using `data-theme` tokens and swapping assets (light/dark logo).

```css
[data-theme="dark"] .logo--light-bg {
  display: none;
}
```

### Continued development

- Add analytics hooks for CTA interactions and FAQ opens.
- Improve modal flow with async submit and loading states.
- Refine testimonial slider with swipe/auto-play + reduced-motion support.

### Useful resources

- [MDN ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/) – helpful for focus management patterns.
- [Josh Comeau: CSS Animations and prefers-reduced-motion](https://www.joshwcomeau.com/) – guidance on motion accessibility.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for the design brief and assets.
