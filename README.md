# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements
- View the optimal layout for the app depending on their device's screen size

### Screenshot

![desktop-design](https://user-images.githubusercontent.com/77099631/160136993-f7cdc7b4-d0d1-4aca-ab29-2b318587fe8a.jpg)

### Links

- Solution URL: [Solution URL here](https://github.com/mohameddwedar689/Order-summary-component-main)
- Live Site URL: [Live site URL here](https://mohameddwedar689.github.io/Order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Variables
- Using rem units

### What I learned

```HTML
<main class="container">
        <!-- image section -->
        <img src="images/illustration-hero.svg" alt="illustration">
        <!-- content section -->
        <div class="content">
            <h1 class="head">Order Summary</h1>
            <p class="description">You can now listen to millions of songs, audiobooks, and podcasts on any 
              device anywhere you like!</p>
            <div class="cridet">
              <div class="icon">
                  <img src="images/icon-music.svg" alt="music">
              </div>
              <div class="info">
                <span class="name">Annual Plan</span>
                <span class="money">$59.99/year</span>
              </div>
              <div class="change">
                  <a href="#">Change</a>
              </div>
            </div>
            <button class="btn-1">Proceed to Payment</button>
            <button class="btn-2">Cancel Order</button>
        </div>
    </main>
```



```css
:root {
    --primary-pale-blue: hsl(225, 100%, 94%);
    --primary-bright-blue: hsl(245, 75%, 52%);
    --natural-pale-blue: hsl(225, 100%, 98%);
    --natural-desaturated-blue:  hsl(224, 23%, 55%);
    --natural-dark-blue: hsl(223, 47%, 23%); 
    --body-color: hsl(225, 100%, 94%);
    --box-shadow: hsl(245deg 75% 52% / 18%);
    --hover-shadow: hsla(245, 83%, 68%, 18%);
    --hover-color: #766cf1;
}
```

```css
@media (max-width: 375px) {
    .container {
        width: 330px;
    }
    .cridet,
    .btn-1 {
        width: 90%;
    }
}
```



## Author

- LinkedIn - [Mohamed Dwedar](https://www.linkedin.com/in/mohamed-dwedar)
- Frontend Mentor - [@mohameddwedar689](https://www.frontendmentor.io/profile/mohameddwedar689)
- Twitter - [@Mohamed72812181](https://twitter.com/Mohamed72812181?s=09)