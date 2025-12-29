# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github Repository](https://github.com/BinitAcharya7/Recipe-Page)
- Live Site URL: [Live site URL](https://recipe-page-beta-eosin.vercel.app/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox

### What I learned

- How to work with Flexbox.
- Using media queries more effectively.
- The object-fit property for images.
- Working with more complex layouts where a lot of reusability saves from a lot of headache.
- Just how great max-width is.

```css
.@media (max-width: 655px) {
    body {
        margin: 0 auto;
        justify-content: flex-start;
        gap: 0;
    }

    img {
        border-radius: 0;
    }
    main {
        padding: var(--spc-500) var(--spc-400);
    }
}

img {
    border-radius: var(--spc-150);
    max-width: 100%;
    /* object-position: center; */
    object-fit: contain;
}

```

### Continued development

- Must get more comfortable with complex layouts, since they have a lot going on.
- Must learn how to plan out in advance what I must do by looking at the required design.
- Must learn more responsive design concepts.
- Must use Figma dev tools better.


### Useful resources

- [Smarter Sizing with CSS](https://www.youtube.com/watch?v=DM244V9KvNs) - Video by Kevin Powell on how to size elements better.
- [rems vs ems](https://youtu.be/pautqDqa54I?si=XDMoABFZNhmjxvW9) - Video providing very clear ways to decide on when to use ems vs rems.
- [Top 10 Advanced Responsivene Design Concepts](https://youtu.be/TUD1AWZVgQ8?si=WgnhbYVucoUiWOwI) - Video explaining ways to make webpages responsive with and without media queries.


## Author

- Website - [Binit Acharya](https://binitacharya.medium.com/)
- Frontend Mentor - [@BinitAcharya7](https://www.frontendmentor.io/profile/BinitAcharya7)
- Twitter - [@Binit_Acharya](https://www.twitter.com/Binit_Acharya)

## Acknowledgments

Thanks to me for not tearing all my hair out.

