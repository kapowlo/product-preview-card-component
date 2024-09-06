# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)

  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [ https://www.frontendmentor.io/solutions/mobile-first-product-preview-card-component-wOpqxP8MiZ]
- Live Site URL: [ https://kapowlo.github.io/product-preview-card-component/]

## My process

### Built with

- HTML
- CSS
- Mobile-first workflow

### What I learned

This was my first time using the picture element.

I shouldn't use a width and a height attribute for my source element

```html
<picture>
  <source
    media="(min-width: 800px)"
    srcset="images/image-product-desktop.jpg"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Eau de Parfum"
    width="320"
    height="350"
  />
</picture>
```

I should not nest an anchor tag inside of a button.Instead I should style the anchor tag to look like a button

### Continued development

I want to start using picture elements or srcset attribute + width descriptor along with sizes attribute in my html files to give the proper images to the user based on their device's viewport width.

## Author

- Frontend Mentor - [@kapowlo](https://www.frontendmentor.io/home)
