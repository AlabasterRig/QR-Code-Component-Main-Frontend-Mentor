# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot


### Links

- Live Site URL: [https://alabasterrig.github.io/QR-Code-Component-Main-Frontend-Mentor/](https://alabasterrig.github.io/QR-Code-Component-Main-Frontend-Mentor/)

## My process

I first started by creating divs in html doc and then styling each and every div according to the design specified.

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

I learned how to use the viewport height attribute and how to centre a div within a div in a different way. This is something which will benefit me in future.


```css
.outer-frame {
    background-color: hsl(212, 45%, 89%);
    position: relative;
    height: 100vh;
    width: 100vw;
    margin: 0;
}

.inner-frame {
    background-color: hsl(0, 0%, 100%);
    position: absolute;
    height: 428px;
    width: 275px;
    top: 50%;
    left: 50%;
    border-radius: 17px;
    transform: translate(-50%, -50%);
    text-align: center;
}
```

### Continued development

I learned how to centre a div in a different way. I had to use attributes that i had ever used before, and I would like to continue learning nw things like this in the future.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/) - This helped me in learning more about the styles I have used in this project. I really liked this site and will use it going forward.
