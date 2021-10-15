# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
  - [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Mobile](images/mobile1.png)
![Desktop](images/desktop2.png)


### Links
- Live Site URL: (https://carolinesilvacer.github.io/mentorgrid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Two topics that I wasn't familiarized with was grid column and media rule, however with some research I found out that they were primordial to this project.
Media rule was the main code to keep my layout responsive on mobile.

Here are some of the code I used (CSS):

```css

@media only screen and (min-width: 700px) {
    .container {
        grid-template-columns: 50% 50%;
    }
    .texto1 {
        grid-area: 1/ 1/ 2/ 3;
    }
}

.container {
    background-color: white;
    display: grid;
    grid-template-columns: 100%;
    .......
    }

```

### Continued development

Padding and margin are areas which I have to focus the most, sometimes I get stuck by trying to make them work, such as positions. I'm practicing these concept to refine my skill.

### Useful resources

- [media rule](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp), (https://www.youtube.com/watch?v=2KL-z9A56SQ) - These links helped me to understand where I had to use the media rule, the video was a real quick learn.
- [grid columns]https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template), (https://www.youtube.com/watch?v=HN1UjzRSdBk) - This video got my attention for the way the teacher explained easily the concepts, I'd recommend it to anyone that wants to learn this concept. (It's in Brazilian Portuguese).


## Author

- Website - [Caroline da Silva Cerqueira](https://github.com/carolinesilvacer)
- Frontend Mentor - [@carolinesilvacer](https://www.frontendmentor.io/profile/carolinesilvacer)
- Twitter - [@kroulune](https://www.twitter.com/kroulune)


## Acknowledgments

Someone who I have to thank is my mentor, friend and inspiration Giovana Assis, she is the person who introduced me to this challenge. I will never be capable of thanking her enough for helping me to develop my skills. 

