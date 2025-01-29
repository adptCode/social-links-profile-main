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

![](./assets/images/screenshot.jpg)


### Links

- Solution URL: https://github.com/adptCode/social-links-profile-main.git
- Live Site URL: https://social-profile-adpt.netlify.app/

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I’ve learned a lot about CSS interactions, especially how `:hover`,  `:focus `, and `:focus-within` work. Initially, I struggled with getting the :focus state to apply properly to my .card-element, but I realized that the issue was caused by the fact that links (`<a>`) inside the `.card-element` were naturally focusable, stealing the focus from the parent container.

To fix this, I learned that `:focus-within` is a better choice when I want the focus effect to apply to the entire `.card-element` whenever any child element (like an `<a>`) is focused. This small change made my styles work correctly both for hover effects and keyboard navigation.

Additionally, I discovered how to remove or customize the default focus outline using `outline: none`; while keeping accessibility in mind. Instead of completely removing it, I learned to use `:focus-visible` to apply focus styles only when navigating with the keyboard, which improves usability without affecting mouse clicks.

Finally, I improved the visual smoothness of my interactions by adding a transition effect, making the color changes feel more natural. Now, my `.card-element` design is both visually appealing and fully accessible, working well for both mouse and keyboard users.


## Author

- Website - https://alessandrodpt.netlify.app/
- Linkedin - https://www.linkedin.com/in/alessandrodpt/
- GitHub - https://github.com/adptcode