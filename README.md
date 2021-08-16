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

![](/screenshots/desktop.png)
![](/screenshots/mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/emekler0729/fem-3-column-preview-card-component-main)
- Live Site URL: [GitHub Pages](https://emekler0729.github.io/fem-3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- Sass 
- Flexbox
- Mobile-first workflow

### What I learned

This project was my first time using Sass and I learned a lot about this CSS extension. The best features of Sass that I learned were:

#### Nesting Sass & BEM Architecture

Combining Sass's nesting and `&` shortcut works perfectly with BEM CSS Architecture. This allowed for simple style of components like `.block` and `.block__element` using this syntax:

```scss
.block {
  &__element {
    // Styles
  }
}
```

#### Mixins 

Mixins was a great way to reduce the amount of duplicate code needed and change only a single variable like, in this case, the card color.

An example of setting a color theme is:

```scss
@mixin theme($color) {
  background-color: $color;

  // More styles that use the color...
}

#card_1 {
  @include theme($card-1-color);
}
```

### Useful resources

- [Sass Website](https://sass-lang.com/) - I used this as a reference for Sass.

## Author

- Website - [Eduard Mekler](https://www.eduard-mekler.com)
- Frontend Mentor - [@emekler0729](https://www.frontendmentor.io/profile/emekler0729)
