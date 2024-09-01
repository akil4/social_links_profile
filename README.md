# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/akil4/social_links_profile](https://github.com/akil4/social_links_profile)
- Live Site URL: [https://akil4.github.io/social_links_profile/](https://akil4.github.io/social_links_profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I was able to replicate the design and add hovering links to the Webpage using the anchor element's href attribute.

```html
<a href="https://github.com/akil4">    
                <div class="element-container">
                    <p class="bold link">GitHub</p>
                </div>
            </a>
            <a href="https://www.frontendmentor.io/profile/akil4">
                <div class="element-container">
                    <p class="bold link">Frontend Mentor</p>
                </div>
            </a>
            <a href="https://www.linkedin.com/in/akil4/">
                <div class="element-container">
                    <p class="bold link">LinkedIn</p>
                </div>
            </a>
```
```css
.element-container {
    padding: 5px;
    border-radius: 7.5px;
    background-color: lightgray;
    margin: 10px;
}

a {
    text-decoration: none;
    color: inherit;
}

.element-container:hover {
    box-shadow: 5px 5px 5px slateblue;
    background-color: black;
    color: white;
}
```

### Continued development

I really need help in picking fonts and colors. I am not sure what to pick for what element and for what purpose. I look forward to choosing fonts and colors that are more user friendly and continue the development process.

### Useful resources

- [Google Fonts](https://fonts.google.com/) - I used Google Fonts to pick the font I think will look good on the web.

- [PlaceHold](https://placehold.co/) - PlaceHold is a very good placeholder image provider that I can use on projects that I am currently devloping and don't have relevant images for.

## Author

- GitHub - [akil4](https://github.com/akil4)
- Frontend Mentor - [@akil4](https://www.frontendmentor.io/profile/akil4)