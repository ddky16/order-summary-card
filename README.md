# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover states for interactive elements

### Screenshot

![Desktop View](/Order%20Summary%20Snapshot%20desktop%20view.png)
![Mobile View](/Order%20Summary%20Snapshot%20mobile%20view.png)

### Links

- Solution URL: [Solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```css
/* I learn new things about background properties, especially background-repeat, background-size, and background-attachment to make the background pattern on the body look static and fill up the viewport like the example given to us */
body {
  font-family: "Red Hat Display", sans-serif;
  margin: 0;
  padding: 0;
  background-color: var(--color-blue-200);
  background-image: url(/images/pattern-background-desktop.svg);
  background-repeat: no-repeat;
  background-size: contain;
  background-attachment: fixed;
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* I am also learning about the line-height property to set your line-height each sentence */
#card-description p {
  font-weight: 100;
  line-height: 1.6;
}
```

## Author

- Frontend Mentor - [@ddky16](https://www.frontendmentor.io/profile/ddky16)
- Twitter - [@code_ddky](https://twitter.com/code_ddky)
