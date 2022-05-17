# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](/design/Cromega_Solution.png)

### Links

- Solution URL: [Nft_Preview_Card](https://github.com/cromega08/nft_preview_card)
- Live Site URL: [CodePen](https://codepen.io/cromega08/pen/wvyJJyG)

## My process

The process was complicated. At start i accomplish to design the card, was really easy and love it the design. The problem was the responsive design, i didn't know how to do a webpage responsive until now, so push myself to study and ended burnedout and without the ability (xd).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS @media queries
- CSS Grid
- Webpage-first workflow


### What I learned

As mentioned before, the main thing i learned was responsive design.

Had problems with the condition of make it responsive for diferents screen sizes because the card scaled with the screen size, but figured out how to resolve it.

My first implementation of a @media query:

~~~css
@media (max-width: 401px) {
    body {
        justify-items: left;
    }
    section {
        width: 72.5vw;
        padding: 3vh 10vw;
    }
    
    aside > div {
        width: 90vw;
        padding: .275em
    }
    
    footer {
        font-size: 1.15em;
        justify-self: center;
    }

    label > img {
        width: 77.5vw;
    }

    #background {
        width: 77.5vw;
    }

    #offer {
        width: 75vw;
        margin: 0 .5em;
        font-size: 1.1em;
    }

    #creator {
        width: 75vw;
        padding-top: 1em;
    }

    #title {
        font-size: 1.5em;
        margin: 0;
        margin-top: .35em;
    }

    #limit {
        font-size: 1.3em;
    }

    #author {
        font-size: 1.3em;
    }
    #description {
        font-size: 1.3em;
        margin: 0;
        margin-top: .3em;
    }
~~~

### Continued development

I want to continue learning everything i can, actually.

In things related to this project, want to learn more responsive design and conquer it.

### Useful resources

- [Learn Responsive Design](https://web.dev/learn/design/) - this website definitely help and motivated me to understanded how to make responsive design. Only learned "@media queries" until date, but feel pretty confident with my evolution.

## Author

- Github - [Cromega08](https://github.com/cromega08)
- Frontend Mentor - [@cromega08](https://www.frontendmentor.io/profile/cromega08)
- CodePen - [Cromega08](https://codepen.io/cromega08)
- Hashnode - [@Cromega08](https://hashnode.com/@Cromega08)


## Acknowledgments

I wanna thank me, because i managed to accomplish this challenge.

***_Superbus et Hedonistic~_***
