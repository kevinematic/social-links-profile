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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./social_links_profile.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/social-links-profile-SDvKt4zhQP)
- Live Site URL: [Social Links Profile](https://kevin-social-links-profile.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom font implementation

### What I learned

This project helped me practice implementing and styling a clean, responsive profile card with interactive elements. Some key learnings include:

- Using CSS variables for consistent color application and easy theme adjustments
- Creating smooth hover transitions on interactive elements
- Implementing custom fonts with @font-face
- Building a responsive layout

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

- [Prompt](https://chatgpt.com/share/680f2bb7-33c4-8010-b9bd-e85b2a8e1b07) - Get rid of built-in link styling.
- [Prompt](https://chatgpt.com/share/680f2c1b-31ac-8010-9f84-c30426f0f131) - Flex-box, brief overview.
- [Prompt](https://chatgpt.com/share/680f2c91-62ec-8010-9c59-c0acf4d8180e) - Media queries, brief overview.
- [Prompt](https://claude.ai/share/4b5ddd20-a430-4d03-9e92-4143ffdf0377) - CSS Custom properties, brief overview.
- [Prompt](https://chatgpt.com/share/680f2d80-f2ec-8010-8034-d8d9782492be) - Make an li element look like a button.
- [Prompt](https://chatgpt.com/share/67fcbfc8-c468-8010-8f3a-7d3fbfa33755) - @font-face rule for .ttf fonts.

## Author

- Frontend Mentor - [@kevinematic](https://www.frontendmentor.io/profile/kevinematic)
- X - Formerly Twitter - [@kevinematic](https://www.twitter.com/kevinematic)
