# frontendmentor.io_Tech-book-club-challange
A challange from FrontenMentor to create a scrollable membership weboage

This is a solution to the [3 Column Preview Card Component challenge on Frontend Mentor](https://cgmatrix.github.io/frontendmentor.io_3-column-preview-card-component/). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Welcome](#welcome)   
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
### Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.
To do this challenge, you need a basic understanding of HTML, CSS, Flexbox & CSS Grid.


### The challenge

Your challenge is to build out this landing page and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So, if you have something you'd like to practice, feel free to give it a go.

Your users should be able to:
- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

### Screenshot

![](./screenshot.jpeg)


### Links

- Live Site URL: [https://github.com/CgMatrix/frontendmentor.io_Tech-book-club-challange](https://cgmatrix.github.io/frontendmentor.io_Tech-book-club-challange/)

## My process

### Built with:

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Pseudo-classes
- Mobile-first workflow

### What I learned:

This challange helped me to improve and gain more skills based on:
- Semantic HTML tags
- CSS flexbox
- Media queries - @media
- Pseudo class - :hover
- Pseudo class - :focus
 
This excersize also helped me improve skills required for developing a responsive web page by starting with mobile first, desktop last.

Example of code snippest after research on MDN:
```html
<ul class="square-bullet-numbers">
  <div>
    <li class="framed-number">1</li>
    <li>Choose your membership tier</li>
  </div>
  <div>
    <li class="framed-number">2</li>
    <li>Get your monthly book selection</li>
  </div>
  <div>
    <li class="framed-number">3</li>
    <li>Join our discussion forums</li>
  </div>
  <div>
    <li class="framed-number">4</li>
    <li>Attend exclusive meetups</li>
  </div>
</ul>
```

```css
  .square-bullet-numbers div:not(:last-child)::before {
    position: absolute;
    content: "";
    display: inline-block;
    top: 16px;
    right: 0px;

    width: 80px;
    height: 80px;
    background-image: url(./assets/images/pattern-arrow.svg);
    background-size: contain;
    background-repeat: no-repeat;
  }
```

### Continued development:

Based on extending skills for future projects, I'm planning to focus more on the following:
- Tailwind

### Useful resources:

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This always helped me to regain knowledge of stuff I've forgotten.
- [CSS Tricks](https://css-tricks.com/) - This is an amazing webiste that contains powerfull spreadsheets.
- [CodePen](https://codepen.io/) - An amazing website to study other's code.

### Experience:

A content property is commanded by a rule. A ::before pseudo-element will not render on the page unless a content property (even content: "";) is explicitly declared.
The pseudo-element behaves as an inline element by default. If you need to set explicit dimensions, margins, or padding, change it to "display: inline-block" or use positioning.
## Author

- Github - [CgMatrix](https://github.com/CgMatrix)
- Frontend Mentor - [@CgMatrix](https://www.frontendmentor.io/profile/CgMatrix)

## Acknowledgments

Big thanks to Frontend Mentor for providing the challenge & design with resources to improve & develop more skills.
