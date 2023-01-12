# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution]((https://www.frontendmentor.io/solutions/order-summary-component-g1SPiRrd4i)
- Live Site URL: [GitHub Pages](https://delanohendrix.github.io/Order-Summary-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I had the idea of making the section containing the product information would grow as more products were added, so I decided to use a container to hold the individual order information.

```html
<div class="order-container">
  <div class="order-info">
    <div class="product-icon">
      <img src="images/icon-music.svg" alt="music note icon" />
    </div>
    <div class="product-info">
      <h3>Annual Plan</h3>
      <p>$59.99/year</p>
    </div>
    <div class="product-change">
      <a href="#">Change</a>
    </div>
  </div>
</div>
```

Resulting in this:
![Screenshot2](/screenshot2.png)

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
