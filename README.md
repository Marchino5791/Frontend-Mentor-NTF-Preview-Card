# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/Marchino5791/Frontend-Mentor-NTF-Preview-Carde](https://github.com/Marchino5791/Frontend-Mentor-NTF-Preview-Card)
- Live Site URL: [https://marchino5791.github.io/Frontend-Mentor-NTF-Preview-Card/](https://marchino5791.github.io/Frontend-Mentor-NTF-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google Fonts](https://fonts.google.com/) - For fonts

### What I learned

I learned to create an hover with overlay effect and an icon:

div class="img" <br />
&emsp;      img src="images/image-equilibrium.jpg" alt="Equilibrium image" class="img-equilibrium" <br />
&emsp;        !-- I'm using this div to create an overlay effect -- <br />
&emsp;        div class="effect" <br />
&emsp;        /div <br />
 /div <br />

.effect { <br />
  background-image: url("images/icon-view.svg");  <br />
  background-repeat: no-repeat; <br />
  background-position: center; <br />
  position: absolute; <br />
  top: 0; <br />
  left: 0; <br />
  width: 295px; <br />
  height: 295px; <br />
  opacity: 0; <br />
} <br />

.effect:hover { <br />
  background-color: var(--transparent_cyan); <br />
  opacity: 1; <br />
} <br />

## Author

- Frontend Mentor - [@marchino5791](https://www.frontendmentor.io/profile/marchino5791)
- LinkedIn - [@Marco Antonio Paolino](https://www.linkedin.com/in/marco-paolino/)
