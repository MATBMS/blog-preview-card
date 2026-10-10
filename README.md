# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Extra Feature](#extra-feature)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Extra Feature

**As a** User<br>
**I need to** have an animation on the card hover<br>
**So that it** improve my user experience

### Screenshot

#### Preview Screenshot

![Preview Screenshot](./docs/preview.jpg)

#### Desktop Screenshot

![Desktop Screenshot](./docs/desktop-screenshot.png)

#### Desktop On Hover Screenshot

![Desktop Screenshot](./docs/desktop-on-hover-screenshot.png)

### Links

- Repository URL: [GitHub Repo](https://github.com/MATBMS/blog-preview-card)
- Live Site URL: [GitHub Page](https://matbms.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

#### Change body background color on hover

To change the background of the `<body>` when hovering over an article using **onlu CSS**, you can use the `:has()` pseudo-class.

```css
body:has(.card:hover) {
  background-color: var(--color-black);
}
```

### AI Collaboration

No AI was used during this project.
