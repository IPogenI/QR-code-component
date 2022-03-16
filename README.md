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
- [Author](#author)

## Overview

  A simple Responsive CSS Flexbox styling of a QR Component in a single webpage.

### Screenshot

![Desktop design preview for the QR code component coding challenge](./screenshots/Screenshot%20of%20Desktop%20Design.png)

![Mobile design preview for the QR code component coding challenge](./screenshots/Screenshot%20of%20Mobile%20Design.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: (https://ipogeni.github.io/QR-code-component/)

## My process

  First copied the boiler code to my VS Code IDE, then started getting the font, declared base body styles. Simultaneously created a new div in HTML for the QR Component and another two divs for the image and the text then went back to styling and styled them using CSS Flexbox. Set background color and text colors, fonts and reduced image size. Final touch was some border-radius both on the image and it's container and some padding to make it look good.

### Built with

- Semantic HTML5 markup
- CSS Flexbox
- CSS Styling

### What I learned

I learned that setting a custom height to a div and setting the box-sizing to border-box, we can't use padding inside the elements of the div and expect it to work properly!


```html
<div class="card">
    <div class="qr-img">
      <img src="./images/image-qr-code.png" alt="qr-code">
    </div>
    <div class="qr-text">
      <h3>Improve your front-end <br> skills by building projects</h3>
      <small>Scan the QR code to visit Frontend <br> Mentor and take your coding skills to <br> the next level.</small>
    </div>
  </div>
```

```css
.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    background-color: hsl(0, 0%, 100%);
    width: 280px;
    height: 430px;
    padding: 15px;
    border-radius: 20px;
    box-shadow: 0px 2px 35px rgb(0 0 0 / 10%)
}

```

### Continued development

I want to refine this piece of work with using bootstrap in the near future.


## Author

- Website - [Protaya Roy](https://github.com/IPogenI)
- Frontend Mentor - [@Pogen](https://www.frontendmentor.io/profile/IPogenI)
- LinkedIn - [@Protaya Roy](https://www.linkedin.com/in/protaya-roy-373022184/)