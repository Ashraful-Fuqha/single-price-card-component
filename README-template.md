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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/single-price-card-component-qcs_T3zTvb)
- Live Site URL: [Add live site URL here](https://ashraful-fuqha.github.io/single-price-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

In this project i have gained more knowledge about the CSS3 grid property.

code snippets, see below:

```html
<section>
      <h2>Monthly Subscription</h2>

      <h1>&dollar;29 <span>per month</span></h1>

      <p>Full access for less than &dollar;1 a day</p>

      <button>Sign Up</button>
    </section>

```
```css
main{
        min-height: 100vh;
        grid-template-columns: repeat(2,420px);
        grid-template-rows: 230px 270px ;
        grid-template-areas: 
                    "first first"
                    "second third";
        place-items: stretch;
        row-gap: 0;
    }
```

### Continued development

I want to learn about the more grid properties and apply SCSS.

## Author

- Website - Definetly
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)
