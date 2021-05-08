# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

- [Desktop Screenshot](/images/desktop_column_preview_card.png)
- [Mobile Screenshot](/images/mobile_column_preview_card.png)

### Links

- Live Site URL: [here](https://arthurgc.github.io/column-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Declare variables and work with them is easy in SASS. Besides, you do not need `:root` to declare or use them.

```css
// Variables
$color-bright-orange: hsl(31, 77%, 52%); 
$color-dark-cyan: hsl(184, 100%, 22%);
$color-very-dark-cyan: hsl(179, 100%, 13%);

// paragraphs
$color-trans-white: hsla(0, 0%, 100%, 0.75); 

//background, headings, buttons
$color-light-gray: hsl(0, 0%, 95%); 

//Fonts
$font-big-display: 'Big Shoulders Display', cursive;
$font-lexend: 'Lexend Deca', sans-serif;
$font-size-h1: 2.5rem;
$font-size-p: .9rem;
$font-size-btn: 1.1rem;

```

### Useful resources

- [SASS Guide](https://sass-lang.com/guide) - This helped me for working with variables and other features in SASS.

## Author

- Github - [ArthurGC](https://github.com/ArthurGC)