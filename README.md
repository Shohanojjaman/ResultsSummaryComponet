# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help me improve my coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

- *Desktop View (1440px)*

![](./assets/images/desktop-device(1440px).png)


- *Mobile View (375px)*

![](./assets/images/mobile-device(375px).png)
### Links

- Solution URL: [Frontend Mentor | Results summary component coding challenge solution](https://your-solution-url.com)
- Live Site URL: [Results Summary Component](https://shohanojjaman.github.io/ResultsSummaryComponet/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Through this project, I learn about custom attributes / data attributes and how to use this. Custom attribute help to an awesome design and also help to keep clean code.

Here is an example of a custom attribute: In this example, we will set the background colors of the elements using the CSS access that we just saw. As the custom attributes are plain HTML attributes, they can be accessed from CSS. For example, we can use attribute selectors to style the background color of the element.

```html
<!DOCTYPE html>
<html>
  
<head>
    <title>Page Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
  
<body>
    <h2>Welcome To GFG</h2>
    <p data-about="blog">Informational text entries</p>
  
  
    <p data-info="blogathon">Blogathon 2021</p>
  
</body>
  
</html>
```
```css
p[data-about='blog'] {
background-color: #C2F784;
}

p[data-info='blogathon'] {
background-color: #DF2E2E;
}
```

## Author

- Frontend Mentor - [@Shohanojjaman](https://www.frontendmentor.io/profile/Shohanojjaman)
- Linkedin - [Shohanojjaman Emon](https://www.linkedin.com/in/shohanojjamanemon/)
- Twitter - [@shohanojjaman_](https://twitter.com/shohanojjaman_)
