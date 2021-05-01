# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMprofileCard/)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMprofileCard/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and CSS3
- Flexbox

### What I learned

Very simple challenge. Only thing worth mentiong is multiple backgrounds set to view width percentage to ensure a flexible background pattern.

```css
body {
  background: url("../images/bg-pattern-top.svg") no-repeat left -40vw
      top -50vw / 90vw, url("../images/bg-pattern-bottom.svg") no-repeat left
      50vw bottom -50vw / 90vw;
  background-color: $dark-cyan;
}
```

### Useful resources

- [Using Multiple Backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Using_multiple_backgrounds) - MDN multiple backgrounds page.

## Author

- Ayula Boyilo
