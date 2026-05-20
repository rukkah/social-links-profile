# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). 

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- Navigate through profile links using only the keyboard
- Experience a responsive layout across different screen sizes
- View a personalized version of the design with custom profile information and links

### Screenshot

![My project screenshot](./images/Screenshot-socialcard.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5
- CSS custom styling
- Flexbox
- CSS Grid
- Mobile-first workflow
- Accessibility-focused styling
- Google Fonts (Inter)

### What I learned

While building this project, I practiced creating responsive layouts using a mobile-first approach and paying closer attention to design details.

Some things I improved during this challenge:

- Using semantic HTML elements such as `main`, `article`, and `nav`
- Creating centered layouts with Flexbox
- Styling profile images with `border-radius`, `object-fit`, and `object-position`
- Understanding why circular images require equal width and height
- Managing responsive sizing with `min()`
- Improving accessibility by styling keyboard focus states

Example:

```css
.card{
 width: min(90%, 380px);
}

img{
 width: 90px;
 height: 90px;

 border-radius: 50%;

 object-fit: cover;

 object-position: center top;
}
```

### Continued development

Going forward, I want to continue improving:

- Responsive design decisions
- Accessibility best practices
- Cleaner CSS structure
- Hover and focus interactions
- Building projects with less reliance on visual trial and error

I also want to keep strengthening my frontend workflow and become faster at translating designs into code.

### Useful resources

- Frontend Mentor challenge briefs
- MDN Web Docs
- CSS Flexbox Guide
- Google Fonts documentation

### AI Collaboration

This project was developed with support from ChatGPT as a learning and review partner.

AI support included:

- Reviewing layout structure
- Debugging image sizing and positioning
- Improving responsiveness
- Explaining accessibility considerations
- Suggesting cleaner CSS approaches while keeping implementation decisions user-led

All code implementation and final styling decisions were completed and adjusted by me.

## Author

- Frontend Mentor - [@rukkah](https://www.frontendmentor.io/profile/rukkah)
- Github - [@rukkah](https://github.com/rukkah)
