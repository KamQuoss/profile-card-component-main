# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

# WORK IN PROGRESS :construction_worker:

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

- Build out the project to the designs provided

### Screenshot :construction_worker:

![](./screenshot.jpg)

### Links :construction_worker:

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process :construction_worker:

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- naming conventions in Sass (finally I've chosen kebab-case-convention for it's readability. :bulb: Fun fact: Sass treat hyphens and underscores as identical) 
- HTML has other tags than <div> :innocent:
- CSS background is limited, alternative I found ::before and ::after useful with fixed positioning
```css
    &::before{
        content: url(/images/bg-pattern-top.svg);
        position: fixed;
        right: 50%;
        bottom: 50%;
    }
    &::after{
        content: url(/images/bg-pattern-bottom.svg);
        position: fixed;
        left: 50%;
        top: 50%;
    }
```
- CSS transform :sparkling_heart:


### Continued development

- Identifying site elements
- Positioning elements
- CSS backgrounds

### Useful resources

- [BEM cheat sheet](https://9elements.com/bem-cheat-sheet/#card+i) - This helped with identifying and naming elements in html.
- [normalize.css](https://github.com/necolas/normalize.css) - This is stylesheet that normalizes styles ond preserves useful defaults. I've used only some rules which I found useful for this project. This repo could be out of date, last commits was made at Nov 2018.
- [htmlcolorcodes](https://htmlcolorcodes.com/color-picker/) - Good looking, useful color picker with color schemes. 
- [CSS values and units](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units) - Comprehensive article on CSS values and units, also relations between them included.

## Author

- LinkedIn - [Kamila Kłosek](https://www.linkedin.com/in/kamila-k%C5%82osek-b16b08a7/)
- Frontend Mentor - [@KamQuoss](https://www.frontendmentor.io/profile/KamQuoss)