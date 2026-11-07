# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Extra feature](#extra-feature)
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

### Extra feature

### Screenshot

![Design preview for the Blog preview card coding challenge](./images/preview.jpg)

### Links

- Repository URL: [GitHub Repo](https://github.com/MATBMS/blog-preview-card)
- Live Site URL: [GitHub Page](https://matbms.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

#### Alt text for decorative images

Decorative images (like the abstract card illustration) should have an empty `alt` attribute: `alt=""`. It tells screen readers to skip the image, so users don't hear a long description that adds nothing. This is different from having no `alt` at all, which can make a screen reader read the file name out loud.

```html
<img class="card-image" src="./images/illustration-article.svg" alt="">
```

### AI Collaboration

This is a project where I act as the Product Engineer, not the developer. I define the requirements and validate every decision, and Claude Code writes the code.
