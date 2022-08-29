# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
 - [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![product preview card design clone](screenshots/screenshot-desktop-view.png)  
Desktop view  

![product preview card active state design clone](screenshots/screenshot-active-state-desktop-view.png)  
Desktop view active state  

![product preview card active state design clone](screenshots/screenshot-mobile-view.png)  
Mobile view  


### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Flexbox
- CSS custom properties
- Mobile-first workflow

### What I learned
- Mobile-first design  
  - Creating design for mobile first then add media query for desktop design
- Hover selector
  - The hover selector gets triggered whenever we hover over an element that has this selector defined in css
- Box shadow
  - Adds a shadow effect around the element
  - Property is set as followed: 
  ```
  box-shadow: X-offset Y-offset blur spread-radius color
  ```
- Transition property
  - Allows transition to occur between two states of an element
  - States can be defined by selectors such as :hover or :active
  - Is actually shorthand for the following properties:
    - transition property
    - transition duration
    - transition timing function
    - transition delay
  ```
  transition: transition-property transition-duration transition-timing-function transition-delay
  ```