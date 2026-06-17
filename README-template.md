# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![QR Code Component Solution](/preview.jpg)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions)
- Live Site URL: [Live QR Code Website](https://mrcelemencious-boop.github.io/QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox layout
- Mobile-first workflow
- Google Fonts (Outfit)

### What I learned

Building this component helped me understand how to perfectly center elements on a webpage. I learned how to use the viewport height (`100vh`) on the body element along with Flexbox properties to center the card horizontally and vertically.

Here is the CSS structure I used to keep the card perfectly centered on any screen size:

```css
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: hsl(212, 45%, 89%);
  font-family: 'Outfit', sans-serif;
}