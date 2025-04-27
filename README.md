# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./social_links_profile.jpg)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/social-links-profile-SDvKt4zhQP)
- Live Site URL: [Social Links Profile](https://kevin-social-links-profile.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Custom font implementation

### What I learned

This project helped me practice implementing and styling a clean, responsive profile card with interactive elements. Some key learnings include:

- Using CSS variables for consistent color application and easy theme adjustments
- Creating smooth hover transitions on interactive elements
- Implementing custom fonts with @font-face
- Building a responsive layout

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
/* CSS custom properties for colors and sizing */
:root {
  --white: #ffffff;
  --green: #c4f82a;
  --grey-dark: #141414;
  --grey-medium: #1f1f1f;
  --grey-light: #333333;
}
```

```css
/* Hover state implementation */
li:hover {
  background-color: var(--green);
  cursor: pointer;
}

li:hover a {
  color: var(--grey-light);
}
```

### Continued development

In future projects, I plan to focus on:

- Implementing more complex animations and transitions
- Exploring CSS Grid for layout alternatives
- Adding accessibility enhancements
- Incorporating JavaScript for interactive features

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/kevinematic)
- Twitter - [@yourusername](https://www.twitter.com/kevinematic)
