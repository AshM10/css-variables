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

- Solution URL: [GitHub](https://github.com/AshM10/css-variables)
- Live Site URL: [Netlify](https://ash-css-variables.netlify.app)

## My process

### Built with

- CSS Variables
- Vanilla JavaScript

### What I learned

- CSS Variables can be updated in JavaScript
- HTML <label> tag
- Difference between nodelist and array
- Use of forEach() method on nodelist
- Dataset contains all data attributes

```html
<label for="spacing">Spacing:</label>
      <input
        id="spacing"
        type="range"
        name="spacing"
        min="10"
        max="200"
        value="10"
        data-sizing="px"
      />
```

```js
function handleUpdate() {
  const suffix = this.dataset.sizing || "";
  document.documentElement.style.setProperty(
    `--${this.name}`,
    this.value + suffix
  );
}
```

### Continued development

Continue with Challenge #4.

### Useful resources

- [Unsplash](https://unsplash.com) - Source of freely-usable images.

## Author

- Website - [Ash Moreno](https://www.ashmoreno.dev)
- Twitter - [@sexy_gravy](https://twitter.com/sexy_gravy)


