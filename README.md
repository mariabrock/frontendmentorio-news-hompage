# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![desktop-1](./screenshot.jpg)
![desktop-2](./screenshot.jpg)
![mobile-1](./screenshot.jpg)
![mobile-2](./screenshot.jpg)
![mobile-3](./screenshot.jpg)
![active-states](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/mariabrock/frontendmentorio-news-hompage)
- Live Site URL: [Github Pages](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<div class="hero-grid">

  <img src="./assets/images/image-web-3-desktop.jpg" alt="desktop image" class="desktop-img" />
  <img src="./assets/images/image-web-3-mobile.jpg" alt="mobile image" class="mobile-img" />

  <h1 class="hero-header">The Bright Future of Web 3.0?</h1>

  <div class="hero-text">
    <p class="text">We dive into the next evolution of the web that claims to put the power of the platforms back into the hands of the people.
      But is it really fulfilling its promise?</p>
    <button>READ MORE</button>
  </div>
</div>
```
```css
.article-container {
  background-color: var(--very-dark-blue);
  color: var(--off-white);
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  text-align: left;
  padding: 3rem 2rem;
  max-width: 400px;
}
```

## Author

- Github - [@mariabrock](https://github.com/mariabrock)
- Frontend Mentor - [@mariabrock](https://www.frontendmentor.io/profile/mariabrock)
- LinkedIn - [@mariabrock](https://www.linkedin.com/in/maria-brock/)
