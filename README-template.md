# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/Tomas1211/Four-card-feature-section)
- Live Site URL: [Add live site URL here](https://tomas1211.github.io/Four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learned to make this desktop version, where there are three columns with one box on each side and two boxes in the center, one above the other. I did this by simply creating three div.row elements. The first and the last only contain one of the articles and the second div contains the two center articles. Then I set their parent's display property to flex, and flex-direction to row.


```html
<div class="container">
      <div class="row">
        <article class="supervisor content-box">
          <h3 class="article-title">Supervisor</h3>
          <p class="article-text">Monitors activity to identify project roadblocks</p>
          <div class="article-image">
            <img src="./images/icon-supervisor.svg" alt="">
          </div>
        </article>
      </div>
      <div class="row">
        <article class="team-builder content-box">
          <h3 class="article-title">Team Builder</h3>
          <p class="article-text">Scans our talent network to create the optimal team for your project</p>
          <div class="article-image">
            <img src="./images/icon-team-builder.svg" alt="">
          </div>
        </article>
        <article class="karma content-box">
          <h3 class="article-title">Karma</h3>
          <p class="article-text">Regularly evaluates our talent to ensure quality</p>
          <div class="article-image">
            <img src="./images/icon-karma.svg" alt="">
          </div>
        </article>
      </div>
      <div class="row">
        <article class="calculator content-box">
          <h3 class="article-title">Calculator</h3>
          <p class="article-text">Uses data from past projects to provide better delivery estimates</p>
          <div class="article-image">
            <img src="./images/icon-calculator.svg" alt="">
          </div>
        </article>
      </div>
    </div>
```
```css
@media (min-width: 48rem) {

  .content .container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 2rem;
  }

}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

I mean I can code the websites pretty close to their original design, but when it comes to detailing, I can't make everything pixel perfect. I still need to learn more about placing elements exactly where I want them to be.


### Useful resources

https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts


## Author

- Website - [Four card feature section](https://tomas1211.github.io/Four-card-feature-section/)
- Frontend Mentor - [@Tomas1211](https://www.frontendmentor.io/profile/Tomas1211)


