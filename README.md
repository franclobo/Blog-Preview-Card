# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![image](https://github.com/franclobo/Blog-Preview-Card/assets/58642949/7eb25300-a03a-4aab-8f01-ee4626782f7e)


### Links

- Solution URL: [Blog-Preview-Card](https://github.com/franclobo/Blog-Preview-Card)
- Live Site URL: [Blog-Preview-Card](https://blog-preview-card-08042024.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

```html
<div class="container">
    <header>
      <img src="./assets/images/illustration-article.svg" alt="ilustration-article">
      <p><span>Learning</span></p>
      <p>Published 21 Dec 2023</p> 
     </header>
     <main>
      <h1>HTML & CSS foundations</h1>
      <p>These languages are the backbone of every website, defining structure, content, and presentation.</p>
     </main>
     <footer>
      <img src="./assets/images/image-avatar.webp" alt="image-avatar">
      <span>Greg Hooper</span>
     </footer>
  </div>
```
```css
header > p > span {
  background-color: var(--primary-color);
  font-weight: bold;
  padding: 5px 10px;
  border-radius: 5px;
  margin: 20px 0;
}
```

### Continued development

Use this for a future project to improve my skills in Restful API's

## Author

- Website - [WebMinds Studio](https://www.webmindsstudio.com/)
- Frontend Mentor - [@franclobo](https://www.frontendmentor.io/profile/franclobo)
- Twitter - [@Pancho2788](https://twitter.com/Pancho2788)

## Acknowledgments

I would like to thank Frontend Mentor for the opportunity to improve my skills in web development and anyone who has helped me in this project.
