# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Code Snippets](#code-snippets)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

1. Optimal layout for the site depending on their device's screen size (Responsive)
2. See hover states for all interactive elements on the page

### Screenshots

[https://imgur.com/a/kpKtOOK](https://imgur.com/a/kpKtOOK) - Desktop 

[https://imgur.com/a/HUW4xz6](https://imgur.com/a/HUW4xz6) - Mobile 

### Live site URL 

[https://sunnyside-responsive.netlify.app/](https://sunnyside-responsive.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

This project allowed me to re-inforce my CSS and Flexbox skills. 
I really enjoyed making the website responsive and adding media queries to make sure it was responsive for multiple devices. 
I used ``` height: fit-content; ``` for the first time in this project which was another new property I learned. 
I also had to overcome a few challenges on the way so I had to research solutions and read documentation to impliment these changes. 
[https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
was a great tool for this alongside StackOverflow for specific questions. 


### Code Snippets

1.
```css
.learn-more::after {
  content: "";
  position: absolute;
  left: -1%;
  bottom: -22%;
  padding: 0.4rem 6.4rem;
  border-radius: 15px;
  background-color: rgba(255, 217, 0, 0.2);
  z-index: 1;
}
```
This code snippet allowed me to add the styling to the 'learn more' elements on the page, which was a subtle design choice but overall really gave the website a nice feel. 
```css
.learn-more:link,
.learn-more:visited {
  color: #23303e;
}
``` 
I also added a hover element so that it matched the colour when it was active.

2.
```css
.helper-center {
  position: absolute;
  top: 75%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
```
This was the first time i've added text inside of a div over an image. 
It was great to impliment this as it's another skill that I have learned due to this project! 

3.
```css
.section-3-info {
  font-family: "Barlow", sans-serif;
  line-height: 1.7;
  font-size: 1.8rem;
  width: 40rem;
  color: #3b675d;
  letter-spacing: -0.03rem;
}
}
```
This is an example of one of the re-usable styles I used during the design. 
It helped me create cleaner and easier to read code and made the whole design process a lot easier and more efficient. 



### Continued development

The challenge is not fully complete as of yet. 

I still have some fixes to impliment that I am aware of:

1. JS to make the mobile navigation work.
2. JS to make the header sticky.
3. Fix the grid sizing issue when responsive @ 50em/ 36em.

I am currently working through a JS course so I will hopefully be able to add these features once I have the skills required to do so. 

As for the flexbox/ grid issue I have tried to fix this problem but I couldn't get it to work without setting a definate height on a div,
which affected the rest of the design whereby the grid would no longer be responsive. I will look into this when I add the JS. 


### Useful resources

- [Colour picker!](https://imagecolorpicker.com/) - This helped me when I needed to match colours specifically to the design specifications. Absolute no-brainer! 
- [Type Scale](https://type-scale.com/) - This is a great tool to make sure that the visual hierarchy of a website is always adheared to. 
- [Semantic HTML](https://htmlreference.io/semantic/) - I used this to make sure my HTML was accurately representing the content on the webpage. 



