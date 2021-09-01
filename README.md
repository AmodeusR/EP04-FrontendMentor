# Frontend Mentor - Order Summary Card Solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

<h3 align="center">Languages</h3>
<p align="center">
  <a href="#">English</a> • <a href="#">Português (Indisponível no momento)</a>
</p>



## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshots

| Desktop View (1280px) | iPad View (768px) | iPhone View (375px) |
|---------|-------|------|
|![Desktop View (1280px)](./screenshots/desktop-1280px-screen.png)|![iPad View (768px)](./screenshots/ipad-768px-screen.png)|![iPhone View (375px)](./screenshots/iphone-375px-screen.png)|




### Links

- Live Site URL: [Github Pages](https://amodeusr.github.io/EP04-FrontendMentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I reinforced my knowledge about Flexbox and Responsive Layout, aiming for a reasonably good UI for basically all screen sizes with minimum Media Queries.

I racked my head to make the image "ignore" the card's padding while being responsive. It was either getting smaller than the div card or wouldn't shrink in smaller screens. Also, I was trying not to use absolute positioning, so I came up with this solution using Flexbox and CSS Calc Function.

```html
<div class="card flex-column">
  <figure class="format-margin flex-column">
    <img class="card__image" src="./images/illustration-hero.svg" alt="illustration of a girl listening to a song and dancing">
  </figure>
[...]
```
```css
.card__image {
  width: calc(100% + 6rem);
  margin-top: -3rem;
  border-radius: 1em 1em 0 0;  
}
```

## Author

- Github - [@AmodeusR](https://www.your-site.com)
- Frontend Mentor - [@AmodeusR](https://www.frontendmentor.io/profile/AmodeusR)


