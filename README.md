# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
Desktop preview:
![Desktop_preview](./design/desktop.png)

Responsive:
![Responsive_preview](./design/mobile.png)

### Links

- Solution URL: [Repository](https://github.com/amoraleslandeo/Stats-preview-card-component.github.io)
- Live Site URL: [Web page](https://amoraleslandeo.github.io/Stats-preview-card-component.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that this property contains a specific area, allowing it to be given attributes only in that space.
```css
.banner {
     position: relative;
```

I learned how to place a color layer on top of a contained image. With this sequence of attributes.
```css
.mask_image {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: #AB5CDB;
```

I learned to blend a color layer with an image with these attributes. 
```css
img {
    mix-blend-mode: multiply;
    opacity: .7511;
```

I learned that this property allows you to crop content that is within a specific area of ​​an image with a background.
```css
    overflow: hidden;
```

In this project I learned to use the SASS language for CSS. This allows me to structure the tags and their properties in the same way as HTML. The advantages of this language are the similarity with HTML and also the lightness of the final file, which allows the code uploaded to the browser to be processed much faster.

## Author

- Website - [Alejandro Morales Landeo](https://github.com/amoraleslandeo/)
- Frontend Mentor - [@amoraleslandeo](https://www.frontendmentor.io/profile/amoraleslandeo)


## Acknowledgments

I wanna say thanks to my daily support [Roberto](https://github.com/RobertoSilvaZ) 🙌😉 who has become my developer Mentor and guide through this process that is just beggining.

