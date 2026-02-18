# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (mobile, tablet, and desktop)
- See hover states for interactive elements
- Interact with the landing page and navigate through different sections

### Links

- Solution URL: [Meet Landing Page - GitHub Repository](https://github.com/jorgeLRM/meet-landing-page)
- Live Site URL: [Meet Landing Page - Live](https://jorgelrm.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS with structured architecture (abstracts, base, components, layout)
- Vite as build tool
- Modern responsive design patterns

### What I learned

Working on this project helped me strengthen several key areas:

**Responsive Design Implementation:**
```css
@media (min-width: 768px) {
  .hero {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
  }
}
```

**SCSS Organization:**
- Implemented a scalable folder structure with abstracts, base components, and layout modules
- Used SCSS mixins for responsive breakpoints
- Leveraged CSS custom properties for consistent theming

**Mobile-first Approach:**
- Started with mobile layouts and progressively enhanced for larger screens
- Optimized images for different device sizes
- Ensured touch-friendly interactive elements

### Continued development

Areas I want to continue improving:

- Advanced CSS animations and transitions for better user experience
- Accessibility features (ARIA labels, keyboard navigation)
- Performance optimization (lazy loading, image optimization)
- Interactive features using JavaScript
- Testing and cross-browser compatibility

## Author

- Frontend Mentor - [@jorgeLRM](https://www.frontendmentor.io/profile/jorgeLRM)
- GitHub - [@jorgeLRM](https://github.com/jorgeLRM)
- X (Twitter) - [@JorgeLrm99](https://x.com/JorgeLrm99)
