# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<br>
<h2 >Mobile Preview</h2>
<p align="center"><br>
  <img src="https://github.com/aparajitdotbee/3-column-preview-card-component/blob/main/final-design/mobile-design.png?raw=true" alt="Mobile Preview" height=500px/>
</p>
<br>
<h2 >Desktop Preview</h2>
<p align="center">
  <img src="https://github.com/aparajitdotbee/3-column-preview-card-component/blob/main/final-design/desktop-design.png?raw=true" alt="Desktop Preview"/>
</p>

### Links

- Solution URL: [GitHub](https://github.com/aparajitdotbee/3-column-preview-card-component)
- Live Site URL: [Netlify](https://3-col-preview-card-component.netlify.app/)

## My process

### Built with

- HTML5
- CSS3

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="column">
      <div class="card-verydarkcyan">
        <img src = "images/icon-luxury.svg" />
        <h2>Luxury</h2>
        <p>Cruise in the best car brands <br>without the bloated prices. <br>Enjoy the enhanced comfort <br>of a luxury 
          rental and arrive <br>in style.</p>
        <div class="button">
          <p>Learn More</p>
        </div>
      </div>
    </div>
```
```css
.container {
    color: hsl(0, 0%, 95%);
    width: auto;
    max-width: 920px;
    margin: 170px 250px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-column-gap: 0;
    align-items: center;
}
```

### Continued development

- Hover animations
- Spacing and indentations
- Margin and Padding
- Display and Position styles

### Useful resources

- [Kevin Powell YouTube Channel](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw)
- [Web Dev Simplified YouTube Channel](https://www.youtube.com/c/WebDevSimplified)

## Author

- Frontend Mentor - [@aparajitdotbee](https://www.frontendmentor.io/profile/aparajitdotbee)
- GitHub - [@aparajitdotbee](https://github.com/aparajitdotbee)
