
# Loopstudios Landing Page

This is my solution to the Loopstudios landing page challenge from Frontend Mentor. The project showcases a responsive landing page for a VR company with interactive elements and mobile-first design.

![Design preview for the Loopstudios landing page](preview.jpg)

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Features](#features)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Deployment](#deployment)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size (desktop: 1440px, mobile: 375px)
- See hover states for all interactive elements on the page
- Navigate using a mobile menu on smaller screens

### Features

- Responsive design that adapts to different screen sizes
- Interactive hover effects on navigation links, creation items, and buttons
- Mobile navigation menu with toggle functionality
- Optimized images for both desktop and mobile viewports
- WCAG compliant color contrast and accessibility features

### Screenshot

*Add your screenshots here after deployment*

### Links

- Solution URL: [Add your solution URL here](#)
- Live Site URL: [https://loopstudio28.netlify.app/](#)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox and CSS Grid for layouts
- Mobile-first responsive design
- JavaScript for mobile navigation toggle
- Google Fonts (Alata 400, Josefin Sans 300)

### What I Learned

This project helped me strengthen my skills in:

- Creating responsive layouts using CSS Grid and Flexbox
- Implementing mobile-first design principles
- Using media queries effectively for different viewport sizes
- Creating interactive elements with CSS transitions and hover effects
- Implementing a mobile navigation menu with JavaScript

```css
/* Example of responsive grid implementation */
.creations-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 30px;
}

@media (max-width: 768px) {
  .creations-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }
}
```

```js
// Mobile menu toggle functionality
document.addEventListener('DOMContentLoaded', function() {
  const hamburger = document.querySelector('.hamburger');
  const closeMenu = document.querySelector('.close-menu');
  const mobileMenu = document.querySelector('.mobile-menu');
  
  hamburger.addEventListener('click', function() {
    mobileMenu.classList.add('active');
    document.body.style.overflow = 'hidden';
  });
  
  closeMenu.addEventListener('click', function() {
    mobileMenu.classList.remove('active');
    document.body.style.overflow = '';
  });
});
```

### Continued Development

In future projects, I want to focus on:

- Enhancing accessibility features
- Implementing more advanced CSS animations
- Optimizing performance for faster load times
- Exploring CSS preprocessors like SASS for more maintainable styling

## Deployment

The site can be deployed using any of these free hosting platforms:

- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

For deployment instructions, see the [Hosting Your Loopstudios Landing Page guide](#).

## Author

- Website - [Your Name](https://your-website.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://twitter.com/yourusername)

     
