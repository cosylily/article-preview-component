# article-preview-component

A project chllenge from frontend mentor. This time it is not just HTML and CSS but it will also use JavaScript. This is a good practice for people who left JavaScript for a while.

# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](./images/webpage.png)

### Links

- Solution URL: [https://github.com/cosylily/article-preview-component.git]
- Live Site URL: [https://comforting-biscochitos-a88302.netlify.app/]

## My process

### Built with

- HTML
- CSS
- Javascript

### What I learned

In this particular project, I learned a lot of new stuff like cropping the image using css, use svg file and able to change its colour, position of css and used ::after for the first time. On top of that, a lot of revision is done for javascript as well. New learning on javascript is on the matching of screensize.

```css
.proud-of-this-css {
  mask-image: url(./images/icon-share.svg);
  background-color: var(--dark-blue);
  height: 20px;
  width: 20px;
  mask-repeat: no-repeat;
  mask-size: contain;
  mask-position: center;
}
```

```js
const proudOfThisFunc = () => {
  const maxwidth = window.matchMedia("(max-width:700px)");
  function checkScreen() {
    if (maxwidth.matches) {
      notPopit();
    } else {
      popIt();
    }
  }
};
```

### Continued development

What I would like to really deepen my knowledge in next is how to properly arrange the components and elements to make it visually nice to the viewers. I would love to learn about blank space.

### Useful resources

- [https://uploadcare.com/blog/how-to-crop-an-image-in-html-and-css/]Never knew that you can always crop the image using CSS which makes everything much simpler.
- [https://stackoverflow.com/questions/43312042/svg-object-change-color-from-external-css] When SVG is presented as an image file, it might be confusing on how to change the colour of the icon. This is helpful to learn how to do it!
- [https://www.youtube.com/watch?v=YEmdHbQBCSQ] Coding2Go youtube video explaining positioning using CSS. Easy to understand. -[https://stackoverflow.com/questions/12483178/how-can-i-make-a-triangle-in-html] To make an triangle using borders. An interesting perspective

## Author

- Website - [https://syafiqahborhan.netlify.app/]
- Frontend Mentor - [@cosylily](https://www.frontendmentor.io/profile/cosylily)
