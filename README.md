# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](.images\Frontendmentor NFT card component finished challenge.png)

### Links

- Solution URL: (https://github.com/branalex94/frontendmentor-NFT-Card-Component)
- Live Site URL: (https://branalex94.github.io/frontendmentor-NFT-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learned how to better use the CSS techniques I haven't used before, like flexbox, on hover properties and styles.

```css
.topSection:hover .eyeContainer,
.eyeIcon {
  display: block;
  cursor: pointer;
}

.eyeContainer {
  display: none;
  position: absolute;
  height: 300px;
  width: 260px;
  z-index: 10;
  top: 0;
  left: 0;
  background: rgba(0, 255, 248, 0.6);
  border-radius: 10px;
}

.eyeIcon {
  position: absolute;
  top: 40%;
  left: 40%;
  background: transparent;
}
```

### Continued development

I'm having ideas of using this component to create a fully built NFT website.

### Useful resources

- (https://stackoverflow.com/) - Stackoverflow as usual helped me to get over many slumps I found on the road.

## Author

- Website - [Brandon Aray](https://github.com/branalex94/)
- Frontend Mentor - [@branalex94](https://www.frontendmentor.io/profile/branalex94)
