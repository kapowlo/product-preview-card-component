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

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML
- CSS
- Mobile-first workflow

### What I learned

This was my first time using the picture element

```html
<picture>
  <source
    media="(min-width: 800px)"
    srcset="images/image-product-desktop.jpg"
    width="600"
    height="900"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Eau de Parfum"
    width="320"
    height="350"
  />
</picture>
```

### Continued development

I want to start using picture elements or srcset attribute + width descriptor along with sizes attribute in my html files to give the proper images to the user based on their device's viewport width.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
