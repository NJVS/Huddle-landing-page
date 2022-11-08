# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

<table>
  <tr>
    <td valign="top">
        Desktop
        <img src="./design/ssDesktop.png">
    </td>
    <td valign="top">
        Tablet
        <img src="./design/ssTablet.png">
    </td>
    <td valign="top">
        Phone
        <img src="./design/ssPhone.png">
    </td>
  </tr>
</table>

### Links

- [Live Demo]()

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Javascript
- [SASS/SCSS](https://sass-lang.com) - CSS preprocessor
- Flexbox
- CSS Grid
- Responsive Web Design

### What I learned

I did go overboard on this project. I didn't use the provided svg background waves, instead, I built randomly generated waves using javascript. But other than that, this project is very simple, and the only Javascript needed is the form validation. I've already done a simple email validation from my previous FrontendMentor challenge([Base Apparel coming soon page](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0)) so I just copy and paste it.

For the randomly generated waves, this script is heavily inspired from a library: [Wavyfy](https://github.com/peacepostman/wavify) by [peacepostman](https://github.com/peacepostman). And if you wanna try it, I recommend using Wavyfy instead of mine. Wavyfy has a lot more functionality and mine is a little messy

Also, I did consider users who turned off their animation on their device `prefers-reduced-motion: reduce`. If you do, it will only generate wave once. And if you are not sure if it's turned off, check the console. I leave a `console.log()` to see if it's `ON` or `OFF`.

### Useful resources

- [Wavyfy by peacepostman](https://github.com/peacepostman/wavify)
- [Wavejs by vedantyadu](https://github.com/vedantyadu/wavejs-updated)
- [The SVG "path" Syntax: An Illustrated Guide by Chris Coyier](https://css-tricks.com/svg-path-syntax-illustrated-guide/)
- [Animate SVG Path Changes in CSS by Chris Coyier](https://css-tricks.com/animate-svg-path-changes-in-css/)
- [codepen SVG Waves by Mikołaj Stolarski](https://codepen.io/grimor/pen/qbXLdN?editors=1010)
- [MDN Docs requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)
- [requestAnimationFrame for Smart Animating by Paul Irish](https://www.paulirish.com/2011/requestanimationframe-for-smart-animating/)
- [RequestAnimationFrame in JavaScript by Suprabha Supi](https://medium.com/geekculture/requestanimationframe-in-javascript-82a913cf8c46)
- [Javascript.info](https://javascript.info) - From the basics to advanced topics with simple, but detailed explanations.
- [Javascript.info - Class](https://javascript.info/class)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [An opinionated styleguide for writing sane, maintainable and scalable Sass.](https://sass-guidelin.es/)