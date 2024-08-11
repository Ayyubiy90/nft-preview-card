# Frontend Mentor - NFT Preview Card Component Solution 🎨

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of Contents 📑

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview 🔎

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Live Site URL: [NFT Card Preview](https://nft-preview-card-seven-alpha.vercel.app/)

## My Process 🛠️

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I Learned

During this project, I reinforced my understanding of HTML structure and CSS styling. Some key learnings include:

- Creating a responsive card layout
- Implementing hover effects
- Using Flexbox for alignment

Here's a code snippet I'm particularly proud of:

```css
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: hsla(178, 100%, 50%, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.card-image:hover .overlay {
  opacity: 1;
  cursor: pointer;
}
```

This CSS creates a smooth hover effect for the NFT image.

### Continued Development

In future projects, I want to focus on:

- Improving my CSS animations
- Exploring more advanced responsive design techniques
- Incorporating accessibility features

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/) - An excellent resource for HTML and CSS references.
- [CSS-Tricks](https://css-tricks.com/) - Great for understanding Flexbox and other CSS concepts.

## Author 👨‍💻

- Website - [Abdullah](https://www.your-site.com)
- LinkedIn - [LinkedIn](https://www.linkedin.com/in/abdullah-a-2940b7260/)
- Frontend Mentor - [Abdullah](https://www.frontendmentor.io/profile/Ayyubiy90)
- Twitter - [Abdullah](https://www.twitter.com/ayyubiy10)
- Instagram - [Abdullah](https://www.instagram.com/ayyubiy_10)

## Acknowledgments 🙏

I'd like to thank Frontend Mentor for providing this challenge and the Frontend Mentor community for their invaluable feedback and support.