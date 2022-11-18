# Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![screenshot](./images/screenshot.png)

### Links
- Live Site URL: [click here](https://migueweb.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

#### **Mix blend mode** 

This property describes how the element blends with the background element.


```html
      <img class="card-header-mobile" src="./images/image-header-mobile.jpg" alt="people working">

      <div class="card-header-filter"></div>
```
```css
.card-header-mobile {
    display: block;
    width: 100%;
    height: 100%;
    position: relative;
    mix-blend-mode: multiply;
    opacity: 0.75;
    z-index: 2;
}
.card-header-filter {
    background-color: var(--soft-violet);
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    z-index: 1;
}
```
### Useful resources

- [Mix blen mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - This helped me learn how it works mix-blend-mode.




## Author
Miguel Amador
- Github: [@migueweb](https://github.com/migueweb)
- Frontend Mentor: [@miguweb](https://www.frontendmentor.io/profile/yourusername)

