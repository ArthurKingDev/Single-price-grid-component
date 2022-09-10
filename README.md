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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![desktop-design](https://github.com/ArthurKingDev/Single-price-grid-component/blob/main/screenhot(1).png)

![mobile-design](https://github.com/ArthurKingDev/Single-price-grid-component/blob/main/screenshot.png)

### Links

- Solution URL: https://github.com/ArthurKingDev/Single-price-grid-component.git
- Live Site URL: https://arthurkingdev.github.io/Single-price-grid-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt the concept and practical use of  CSS Grid. 

```css
.grid-container {
        display: grid;
        grid-template-columns:  350px 350px;
        grid-template-rows: 220px 250px;
        grid-auto-flow: row;
    }

    .item-1 {
        grid-column: 1 / span 2;
        grid-row: 1 / 1;
    } 
    .item-2 {
        grid-column: 1 / 1;
        grid-row: 2 / 2;
    }

    .item-3 {
        grid-column: 2 / 2;
        grid-row: 2 / 2;
    }
```

### Continued development

- Solve more layout challenges.
- Practice more CSS Grid.


### Useful resources

- [CSS Grid layout module](https://www.w3schools.com/css/css_grid.asp) - This helped me get a better understanding of CSS Grid layout.
- [Grid item](https://www.w3schools.com/css/css_grid_item.asp) - This is an amazing article which helped me get the desktop layout. I'd recommend it to anyone still learning this concept.



## Author
- Frontend Mentor - [ArthurKingDev](https://www.frontendmentor.io/profile/ArthurKingDev)
- Twitter - [arthurkings0097](https://twitter.com/arthurkings0097)


