# Make It Real - NFT preview card component

This is a solution to the NFT preview card component project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Build a component based on a plain image design
- Adapt css styling to be responsive

### Screenshot

![screenshot of the proyect](./images/screenshot.png)

## My process

To begin with, we analized the image proposed as design to identify the structural elements for HTML file. Then we applied that structure to the HTML file. Later, we applied styling with css for the mobile design and the active state of liked elements. Finally we applied the required modifications for the desktop design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned a couple of handy css properties:

```css
div.img-hover {
  visibility: hidden;
  position: relative;
}
a.img-link:hover .img-hover {
  visibility: visible;
}
.eye-icon {
  position: absolute;
  bottom: 0;
  object-fit: scale-down;
}
```

I also remembered and practiced some other properties:

```css
#info {
  display: flex;
  justify-content: space-between;
}
```

### Continued development

I need to keep getting familiar with flex more properties. Also have to reinforce knowledge on position absolute and position relative.

### Useful resources

- [Flex-box Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me to align correctly some elements.
- [Free Code Camp on Positioning](https://www.freecodecamp.org/news/css-positioning-position-absolute-and-relative/) - This helped me to set the :hover state for the image.

## Author

- [LinkedIn](https://www.linkedin.com/in/juan-orjuela/)
- [Behance](https://www.behance.net/juan_o)

## Acknowledgments

Special aknowledgments to Camilo Pimentel, coding partner on this task, and to Germán Escobar, teacher and mentor for supervising our process.


