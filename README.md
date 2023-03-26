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

================================================================================================

## Overview

### Screenshot

![the solution screenshot](/screenshot.jpg)

================================================================================================

## My process

I am a French beginner developer, I started to learn HTML and CSS about 2 weeks ago. 
I first did the measurements of the design on photoshop before attacking the html structure. 
After the html, I had a little trouble because I couldn't center my main block, even if I used the "align-items: center" property. 
So I started by putting the rest in place and I came back to this problem after I did my best to recreate this design. 
In the end the only way I found to center the main block is to use margins at the top and bottom. 

--I added some shadow that was not requested because I think it looks good. 

### Built with

- Semantic HTML5 markup
- CSS basic properties
- Flexbox

================================================================================================

### What I learned

I learned that you could put the body in a flex display, I thought the body was not affected by the displays. 

```css
body {
  display: flex;
}
```
I discovered to use ":root" by chance. The pseudo-class
can be useful when declaring global custom CSS properties (thanks MDN): 
```css
:root {
  --main-color: hotpink;
  --pane-padding: 5px 42px;
}
```
I used it for the different colors of the challenge, I put "var(--x)" to reuse what we define above. 
for example : 
```css
:root {
    --banckground-color: hsl(212, 45%, 89%);
    --White: hsl(0, 0%, 100%);
    --Light-gray: hsl(212, 45%, 89%);
    --Grayish-blue: hsl(220, 15%, 55%);
}
body {
    background: var(--banckground-color);
}
.main {
    background: var(--White) ;
}
```
================================================================================================

### Continued development

I would like to make an automatic qr-code generator. But I can't do it now.
I will come back on this project to make the modifications I want when I have the necessary skills, if I don't forget it 😭.

================================================================================================

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/sid-shinseo)
