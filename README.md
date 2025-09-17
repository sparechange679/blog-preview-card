# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%202025-09-17%20at%2006-11-39%20Frontend%20Mentor%20Blog%20preview%20card.png)

### Links

- Solution URL: [Blog Preview Card](https://github.com/sparechange679/blog-preview-card.git)
- Live Site URL: [Blog Preview Card](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Local Font Loading for privacy

### What I learned

While working on this project, I reinforced my knowledge of CSS custom properties, responsive design principles, and accessibility best practices. I particularly focused on creating a clean, maintainable code structure.

One technique I was proud of implementing was the smooth hover effect on the card and title:

```css
.blog-card {
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.blog-card:hover {
  transform: translate(-2px, -2px);
  box-shadow: 12px 12px 0px var(--gray-950);
}
```

I also implemented a privacy-focused approach by using local font files instead of CDN-hosted fonts:

```css
@font-face {
  font-family: 'Figtree';
  font-style: normal;
  font-weight: 500;
  src: url('./assets/fonts/figtree-v9-latin-500.woff2') format('woff2');
}
```

### Continued development

In future projects, I want to focus on:

Implementing more complex CSS animations and transitions

Exploring CSS Grid for more complex layouts

Improving my skills in accessibility and semantic HTML

Experimenting with CSS methodologies like BEM for better code organization

### Useful resources

- [Google Webfonts Helper](https://gwfh.mranftl.com/fonts/figtree?subsets=latin) - Always helpful for understanding Font usage in my site.
- [Frontend Mentor](https://www.frontendmentor.io/) - Great for practicing front-end skills with real-world projects.

## Author

- Github - [Blessings Kishindo Sabuni](https://github.com/sparechange679)
- Frontend Mentor - [@sparechange679](https://www.frontendmentor.io/profile/sparechange679)

## Acknowledgments

I'd like to thank the Frontend Mentor community for providing helpful feedback and inspiration. Seeing how others approach the same challenges has been invaluable for improving my skills.
