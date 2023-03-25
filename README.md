# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

The challenge requires you to build a preview card component for an NFT marketplace. You need to implement the design provided in Figma, which includes several interactive elements, such as hover effects.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution](https://github.com/Max88-git/nft-preview-card-component)
- Live Site URL: [Live](https://max88-git.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learnt

Through this challenge, I learnt how to create more complex designs using CSS. I also learnt how to implement interactive elements such as hover effects.

I experimented using the CSS @import rule to import Google fonts.

```css
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap");
```

I also learnt how to create an overlay image icon on hover.

```css
.img-view {
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  background-color: hsla(178, 100%, 50%, 0.5);
  display: none;
}

.img-view img {
  position: absolute;
  width: 50px;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

### Continued development

I plan to continue practicing my CSS skills by completing more Frontend Mentor challenges. For my upcoming projects, I need to concentrate on using advanced CSS to create effects, especially with box-shadows. There are undoubtedly several quick generators that I could investigate.

### Useful resources

[MDN Web Docs](https://developer.mozilla.org/en-US/) - This is my go-to resource for web development documentation.

[How to Import Google Fonts in CSS File](https://www.w3docs.com/snippets/css/how-to-import-google-fonts-in-css-file.html#:~:text=Find%20the%20font%20and%20click,paste%20the%20codes%20you%20need.) - Tried something new with using the CSS @import rule to import Google fonts, rather than adding a link to the `<head>` of my HTML.

[Learn how to style an hr element with CSS](https://www.w3schools.com/howto/howto_css_style_hr.asp) - This tutorial helped me to figure out how to style the `<hr>` element in CSS.

[How To Create an Overlay Image Icon on Hover](https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me to add an overlay to the image on hover.

[Using only CSS, show div on hover over another element](https://stackoverflow.com/questions/5210033/using-only-css-show-div-on-hover-over-another-element) - This Stack Overflow question helped me to figure out how to show the view icon on hover.

## Author

- Website - [Max Lockwood](https://www.maxlockwood.uk/)
- Frontend Mentor - [@Max88-git](https://www.frontendmentor.io/profile/Max88-git)
- Twitter - [@maxlockwood88](https://twitter.com/maxlockwood88)
