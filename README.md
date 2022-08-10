# Frontend Mentor - Stats Preview Card Component Solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size.

### Screenshot

![](./images/stats-preview-card-component-desktop.png)
![](./images/stats-preview-card-component-mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/wesleyjacoby/Stats-Preview-Card-Component)
- Live Site URL: [GitHub Pages](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I had some issues with the automatic resizing of the image in the desktop view, however, I managed to find a solution with the following code:

To see how you can add code snippets, see below:

```css
img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: cover;
}
```

Specifically the `object-fit: cover` code.

### Continued development

This one was a easier challenge compared to the full webpages I've tried, but I still seem to be getting slightly stuck when it comes to images. I feel my responsive design was easier with this challenge though.

## Author

- Frontend Mentor - [@wesleyjacoby](https://www.frontendmentor.io/profile/wesleyjacoby)