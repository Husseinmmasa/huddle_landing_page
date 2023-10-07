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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/images/website_screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Sass
- Mobile-first workflow


### What I learned

In this challenge I learnt more about how to style forms and input fields in general. I specifically learnt about how to remove the blue outline when focusing on the input field and also styling the invalid cases.

Also in this challenge I have started to get familiar with the use of sass for compiling css and also the use of BEM.

Consider the code snippets below:


```html
<input type="email" name="email" class="input_email">
```
```css
.input_email {
  font-size: 22px;
  font-family: 'Open Sans', sans-serif;
  height: 50px;
  width: 100%;
}

.input_email:invalid {
  border: 1px solid red;
}

.input_email:focus {
  outline: none;
}
```

### Continued development

I want to improve my knowledge in web development by starting to build pages that involves the integration of some JavaScript beacause the main building blocks for the best website is HTML, CSS and JavaScript.


### Useful resources

- [Curved Backgrounds](https://fireship.io/lessons/wavy-backgrounds/) - This helped me to learn how to create curved backgrounds by using figures such as ellipses and circles that are displayed over each other.
- [Outline Borders](https://www.tutorialrepublic.com/faq/how-to-remove-outline-around-text-input-boxes-in-chrome-using-css.php) - This article helped me understand how to remove the outline borders on the input field which are a default in many modern browsers.
- [Sass and BEM](https://youtu.be/jfMHA8SqUL4?si=pBwGL7_XXocsVSgD) - This video from the youtuber coder coder helped me to understand many concepts about Sass workflow and also BEM.


## Author

- Frontend Mentor - [@Husseinmmasa](https://www.frontendmentor.io/profile/Husseinmmasa)
- X (Twitter) - [@hadle_b](https://www.twitter.com/hadle_b)


