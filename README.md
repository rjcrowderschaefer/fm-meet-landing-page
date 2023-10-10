# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size: mobile at 375px, tablet at 768px and desktop at 1440px)
- See hover states for interactive elements on the desktop screen size

### Screenshot

![Desktop](https://i.imgur.com/OQDNUDM.png)

### Links

- [GitHub Repo](https://github.com/rjcrowderschaefer/fm-meet-landing-page)
- [Live Site URL](https://main--classy-beignet-7077e9.netlify.app/)

## My process

I used a mobile first approach to develop this process, beginning with the mobile layout and expanding to the tablet and desktop layouts using a CSS media query and adjusting the CSS grid sizing. Where possible I used semantic HTML and was diligent on when and where I used classes versus ids throughout the development process. I made sure to include accessibility components like alt text with images.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project was surprisingly challenging when it came to working with the various grid components. I especially had trouble implementing flexbox to center and align elements similar to what I've done with previous projects. I was able to resolve the issues for some of the grid areas and implemented margin spacing for other elements as necessary. This project also allowed me to practice working with the CSS `background` property to include an image, including how to manipulate the image to cover the entire element using CSS.


```html
<div class="num-container" id="cont-02">
          <div class="vl"></div>
          <div class="num-bullet num-02">02</div>
        </div>
```
<!-- I worked through how to include a vertical line as a part of building the number element -->

```css
.num-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  margin-bottom: 60px;
}

.vl {
  border-left: 1px solid #87879d;
  opacity: 0.25;
  height: 84px;
}

.num-bullet {
  color: #87879d;
  font-size: 1.6rem;
  font-weight: 900;
  line-height: 2.6rem;
  border: 1px solid rgba(134, 135, 157, 0.25);
  border-radius: 29px;
  width: 56px;
  height: 56px;
  padding: 15px 15px 15px 19px;
  background-color: #fafafa;
}
```
<!-- The corresponding CSS that I implemented to achieve the vertical line and circle for the number container -->

## Author

- LinkedIn - [RJ Crowder-Schaefer](https://www.linkedin.com/in/rjcrowderschaefer/)
- Frontend Mentor - [@rjcrowderschaefer](https://www.frontendmentor.io/profile/rjcrowderschaefer)
- GitHub - [@rjcrowderschaefer](https://github.com/rjcrowderschaefer)
