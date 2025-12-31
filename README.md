# Digitalbank Landing Page

Responsive marketing page for a fictional digital bank. Built from the supplied design assets with a focus on clean layout, hover/active states, and a functional mobile menu.

## Overview

- Users see responsive layouts from mobile to desktop.
- Navigation collapses into a hamburger menu with smooth open/close.
- CTA buttons, navigation, and article links include hover/focus states.
- Content and styles align with the provided design system (colors, typography, spacing).

## Tech & Approach

- Semantic HTML5 with accessible labels for interactive controls.
- CSS custom properties, Flexbox, and CSS Grid for layout; gradient CTA styling.
- Mobile-first responsiveness and sticky header for quick navigation.
- Lightweight vanilla JS to toggle the mobile navigation state and lock body scroll.

## Running locally

1. Clone the repo.
2. Open `index.html` in your browser (no build step required).

## File guide

- `index.html` – page structure, hero/features/articles, footer, and nav markup.
- `style.css` – design tokens, responsive layout rules, hover/active states.
- `images/` – provided icons, backgrounds, and article/hero assets.
- `design/` – reference JPGs for mobile/desktop and active states.

## Future ideas

- Add focus trap to the mobile menu for tighter accessibility.
- Integrate a simple contact form with validation.
- Swap inline background images for `picture`/`source` elements for finer art direction.
