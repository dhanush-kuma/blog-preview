# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%20from%202024-09-09%2011-53-10.png)

### Links

- Solution URL: [github](https://github.com/dhanush-kuma/blog-preview)
- Live Site URL: [vercel](https://blog-preview-cyan.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was a great challenge, I learned how to use hover, tranform, transition all these for zoom in animation, one other thing that posed a challenge was overflow in css to prevent image from overflowing, by using flexbox the required responsiveness was met.

```css
.card {
    background-color: hsl(0, 0%, 100%);
    width: 336px;
    display: flex;
    flex-direction: column;
    padding: 20px;
    border: 1px solid black;
    border-radius: 20px;
    box-shadow: 10px 10px black;
    transition: transform 0.3s ease;
}
.card-image {
    border-radius: 10px;
    overflow: hidden;
    position: relative;
    margin-bottom: 25px;
}
.card:hover .card-image img {
    transform: scale(1.1);
}
.card:hover {
    transform: scale(1.05);
}
```


### Continued development

I want to get better at making responsive frontend, this solution work but may not be an ideal solution, if there are no ideal solutions then a better solution, overall this challenge was fun.

## Author

- Website - [Dhanush Kumar](https://www.dhanush-kumar.in)
- Frontend Mentor - [@dhanush-kuma](https://www.frontendmentor.io/profile/dhanush-kuma)

## Acknowledgments

Keep Learning!
