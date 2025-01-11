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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop Screenshot](./desktop.png)
![Mobile Screenshot](./mobile.png)

### Links

- Solution URL: [github.com/soldochris/NFT-preview-card](https://github.com/soldochris/NFT-preview-card)
- Live Site URL: [soldochris.github.io/NFT-preview-card](https://soldochris.github.io/NFT-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to display an icon when hover an image using pseudo elements:

```html
<div class="image-card">
  <img src="./images/image-equilibrium.jpg" alt="image equilibrium">
</div>
```
```css
& .image-card{
      width: 100%;
      border-radius: 10px;
      display: block;
      position: relative;
      display: inline-block;
      overflow: hidden;

      & img{
        width: 100%;
        display: block;
        cursor: pointer;
      }
    }

    & .image-card::before{
      content: "";
      position: absolute;
      top: 50%;
      left: 50%;transform: translate(-50%, -50%);
      display: flex;
      justify-content: center;
      align-items: center;
      background-image: url(./images/icon-view.svg);
      background-size: 40px;
      background-position: center;
      background-repeat: no-repeat;
      background-color: rgba(0, 255, 247, 0.3);
      width: 100%;
      height: 100%;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.3s ease;
    }

    & .image-card:hover::before{
      opacity: 1;
    }
```

## Author

- Website - [christiansoldevilla.tech](https://christiansoldevilla.tech/?i=1)
- Frontend Mentor - [@soldochris](https://www.frontendmentor.io/profile/soldochris)
- LinkedIn - [/christian-soldevilla](https://www.linkedin.com/in/christian-soldevilla/)