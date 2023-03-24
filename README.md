# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

This is how it looks on desktop size computers
![Desktop view](images\desktop-screenshot.png)

This is how it looks on mobile
![Mobile view](images\mobile-screenshot.png)

### Links

- Solution URL: [My solution](https://your-solution-url.com)
- Live Site URL: [live site of the product preview](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Google Fonts

### What I learned

For this project, I learned how to use the picture element and finally got to put my knowledge of grid after series of Youtube videos.

Here are the code snippets of some of the new things I learned, see below:

Got a bit confused on how to include different photos for different screen width and the code snippet helped me achieve the outcome I wanted.

```html
<picture>
  <source media="(max-width:1023px)" srcset="images\image-product-mobile.jpg" />
  <img src="images\image-product-desktop.jpg" class="product-image" />
</picture>
```

First time using a grid container and for this project I used the following code snippet below to achieve the desired outcome.

```css
@media (min-width:1023px) {
    .container{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        max-width: 600px;
        border-radius: 15px 15px 15px 15px;
    }
```

### Continued development

I will look into building more projects using the grid container so I can be confortable with them.

### Useful resources

- [The picture element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This is an amazing article which helped me finally understand how to use the picture element. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Obikaviola](https://www.frontendmentor.io/profile/Obikaviola)
- Twitter - [@obika_viola](https://www.twitter.com/obika_viola)