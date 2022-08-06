# css-variables

This is a solution to the [CSS Variables Challenge on #JavaScript30](https://javascript30.com). 30 day vanilla JS coding challenge.

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

- Change Spacing, Blur, and Base Color by moving the mouse on the range.

### Screenshot

![Screen Shot 2022-08-06 at 3 08 53 PM](https://user-images.githubusercontent.com/89284873/183264696-ebc147b4-10f5-4c0c-ba4b-35a2f6285ec4.png)

### Links

- Solution URL: [GitHub](https://github.com/AshM10/javascript-drum-kit)
- Live Site URL: [Netlify](https://ash-js-drumkit.netlify.app)

## My process

### Built with

- CSS custom properties
- Flexbox
- Vanilla JavaScript

### What I learned

- The keyboard input element
- Keydown event listener
- Data Attributes
- JS Window (BOM)

To see how you can add code snippets, see below:

```html
<div class="keys">
  <div data-key="65" class="key">
    <kbd>A</kbd>
    <span class="sound">clap</span>
  </div>
</div>
```

```js
const keys = document.querySelectorAll(".key");
keys.forEach((key) => key.addEventListener("transitionend", removeTransition));
window.addEventListener("keydown", playSound);
```

### Continued development

Continue with Challenge #2.

### Useful resources

- [Key Code](https://www.toptal.com/developers/keycode) - Helped me get the JavaScript Enevnt Keycode Info

## Author

- Website - [Ash Moreno](https://www.ashmoreno.dev)
- Twitter - [@sexy_gravy](https://twitter.com/sexy_gravy)


