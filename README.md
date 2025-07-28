# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![![alt text](screenshot.png)](./assets/images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/solution-blog-preview-card-AF70xEsUFE)
- Live Site URL: [Add live site URL here](https://nick-rinsky.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5
- CSS custom properties
- Flexbox
- BEM methodology
- Google Fonts (@import)
- Git & GitHub (CLI)

### What I learned

This was my second project where I translated design into clean HTML and CSS code from scratch.

I learned:
- How to structure semantic HTML with BEM naming
- How to connect local and remote fonts using @import and @font-face
- How to use CSS variables for colors and spacing
- How `flexbox` handles layout, spacing, and alignment
- That `img` and `svg` elements should be set to `display: block` to avoid unwanted whitespace
- How `:hover` and `transition` can be used to enhance interactivity
- How to make a component responsive using `max-width`
- That using `font` as a CSS variable doesn't work due to strict syntax requirements

To see how you can add code snippets, see below:

```html
<article class="card">
    
      <img class="card__blog-img" src="assets/images/illustration-article.svg" alt="">

      <p class="card__category">Learning</p>
      <p class="card__publish-date">Published 21 Dec 2023</p>

      <h1 class="card-title">
        <a href="#" class="card__title-a">HTML & CSS foundations</a>
      </h1>

      <p class="card__descriptoin">These languages are the backbone of every website, defining structure, content, and presentation.</p>
      
      <div class="card__author">
        <img class="card__author-img" src="assets/images/image-avatar.webp" alt="Greg Hooper">
        <p class="card__author-name">Greg Hooper</p>
      </div>

  </article>
```
```css
main {
    display: flex;
    min-height: 100vh;
    align-items: center;
    justify-content: center;
    padding: 16px;
}

.card {
    max-width: 384px;
    min-width: 327px;

    background-color: var(--white);
    padding: 24px;
    border-radius: 20px;
    border: 1px solid var(--gray-950);
    box-shadow: 8px 8px 0px 0px var(--gray-950);
}

.card__blog-img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin: 0 0 24px 0;
    display: block;
}

.card__title-a {
    text-decoration: none;
    color: var(--gray-950);
    transition: color 0.2s ease;
}

.card__title-a:hover {
    color: var(--yellow);
}

```

### Continued development

I plan to focus on:

- Responsive Design
- Media Queries
- Crossbrowsing
- Animation / Transformation 
- CSS Methodologies
- CSS preprocessors
- CSS frameworks


### Useful resources

## Author

- Frontend Mentor - [@Nick-Rinsky](https://www.frontendmentor.io/profile/Nick-Rinsky)
- Twitter - [@nick_rinsky](https://x.com/nick_rinsky)

## Acknowledgments

Big shoutout to myself — for staying persistent, learning deeply, and pushing through every step of the process. I also appreciate the Frontend Mentor community for inspiring clean and thoughtful code practices.
