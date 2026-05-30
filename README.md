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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup (article, picture, section)
- CSS Flexbox
- Responsive design with Media Queries
- Google Fonts (Fraunces + Montserrat)
- CSS Reset
- `object-fit` and `<picture>` element for responsive images
- Mobile-first approach

### What I learned

This was my first project where I learned by building directly instead of watching tutorials, and it made a huge difference in how much actually stuck.

The biggest things I picked up:

- **Flexbox** — understanding how parent and child elements interact, and how `justify-content` and `align-items` work together to center things on the page.
- **Responsive images with `<picture>`** — the image wasn't fitting properly inside the card at first. I learned to use `object-fit: cover` along with `height: 100%` to make it fill its container correctly without stretching.
- **Media queries** — switching the card layout from vertical (mobile) to horizontal (desktop) by changing the flex direction of the article.
- **Units** — understanding when to use `em`, `px`, or `%` and how percentage units behave depending on their parent element.
- **CSS Reset** — adding `margin: 0`, `padding: 0`, and `box-sizing: border-box` to prevent unexpected browser defaults from breaking the layout.

### Continued development

- I want to get more comfortable with CSS Grid and understand when to use it over Flexbox.
- I want to practice responsive design more — especially understanding breakpoints better.
- I'd like to improve at reading and using `em` and `rem` units confidently.

## Author

- Frontend Mentor - [@Purvjadh](https://www.frontendmentor.io/profile/Purvjadh)
