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
- [Author](#author)

## Overview

My challenge is to build out this QR code component and get it looking as close to the design as possible.

### Screenshot

![](screenshot.png)

### Links

- Solution URL: https://github.com/ozanweb/qr-code-component-main/
- Live Site URL: https://ozanweb.github.io/qr-code-component-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

* I learned how to center an element (child_element) vertically using css ruleset below;

      ```css
      .parent_element {
        position: absolute;
        top:0; bottom;0; left:0; right:0;
      }

      .child_element {
        position: relative;
        top: 50%;
        transform: translateY(-50%)
      }
      ```

* Setting image with to 100% globally makes all images fill the width of their parent element making them responsive

      ```css
      img {
        width: 100%
      }
      ```

* Using ```root``` selector we can change the default setting of web browser that it uses for all websites.
* My responsive design approach is ```font-size``` based which means size, paddings, margins of any text resizes based on the ```font-size``` of its element.
* CSS unit "rem", where the letter "r" stands for "root", is a unit which uses the ```font-size``` of the ```root``` element.

* The code below is interpreted as "apply the rulesets inside it when the screen size of the device is 800px or above".
      ```CSS
      @media screen and (min-width: 800px) {
        <!-- rulesets go here -->
      }
      ```

### Continued development

* There are other approaches to achieve a responsive design using CSS. Which approach to use depeneds on the browsers version of the client (or audience) who will visit the site mostly. I am currently focusing on most basic approaches to accomplish responsive design to make sure that my site will look okay on older browsers.
* I am also interested in learning other methods of aligning elements vertically.

### Useful resources

- (https://caniuse.com/) - This helps you to see, on which browsers the CSS property used, is supported

## Author

- Frontend Mentor - [@ozanweb](https://www.frontendmentor.io/profile/ozanweb)
- LinkedIn - [@ozanpalanci](https://www.linkedin.com/in/ozanpalanci/)
