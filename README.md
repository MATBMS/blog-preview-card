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

**As a** visitor using a mouse on desktop,<br>
**I want to** see the colors change when I hover the card,<br>
**so that** I get visual feedback that I am pointing at it.

### Screenshot

#### Preview

![Design preview for the Blog preview card coding challenge](./images/preview.jpg)

#### Desktop

![Desktop screenshot of the blog preview card](./images/desktop-screenshot.png)

#### Desktop on hover

![Desktop screenshot of the blog preview card on hover, with a black background and a yellow border and shadow](./images/desktop-on-hover-desktop.png)

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

#### Changing the page background when hovering the card

CSS selectors can only style an element or its children, so hovering the card cannot normally change the `body`. The `:has()` selector solves this: `body:has(.card:hover)` means "the body that contains a hovered card". I wrapped it in `@media (hover: hover)` so it only runs on devices with a mouse, not on touch screens.

```css
@media (hover: hover) {
  body:has(.card:hover) {
    background-color: black;
  }
}
```

### AI Collaboration

This is a project where I act as the Product Engineer, not the developer. I define the requirements and validate every decision, and Claude Code writes the code.
