# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./SocialLinks_Solution.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/social-links-profile-using-html-and-css-DrLZ8poKzx)
- Live Site URL: (https://josenegrete123.github.io/Social-Links-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Learned how to do better naming conventions using BEM methodology. Also, learned how to change the hover state of two different elements, when only 1 element is hovered.

To see how you can add code snippets, see below:

```html
      <div class="card">
        <div class="card__profile-pic"></div>
```
```css
.card__links__button:hover, .card__links__button:hover .card__links__button__placeholder {
    background-color: var(--green);
    cursor: pointer;
    color: var(--grey-700);
}
```

### Continued development

Focus on better structuring the HTML and naming convention of the classes.

### Useful resources

- [BEM Methodology](https://www.toptal.com/css/introduction-to-bem-methodology) - This helped me better name my classes.
- [Hover one element, effect multiple](https://stackoverflow.com/questions/1462360/css-hover-one-element-effect-for-multiple-elements) - This is helped me figure out how to manipulate multiple elements when hovering only one element.

## Author

- GitHub - [Jose Negrete](https://github.com/josenegrete123/Social-Links-Project)
- Frontend Mentor - [@josenegrete123](https://www.frontendmentor.io/profile/josenegrete123)