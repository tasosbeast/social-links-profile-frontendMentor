# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for all interactive elements on the page

### Screenshot

[./assets/images/screenshot.png](./assets/images/screenshot.png)

### Links

- Solution URL: [Add your Frontend Mentor solution URL here]
- Live Site URL: [https://social-links-tasosbeast.netlify.app/](https://social-links-tasosbeast.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Custom font implementation (Inter font family)
- Accessible design patterns

### What I learned

During this project, I focused on implementing:

- Proper CSS reset and modern CSS properties
- Custom font loading with @font-face
- CSS custom properties for consistent theming
- Accessible HTML structure with proper ARIA roles
- Interactive hover states for social links
- Responsive design that works across device sizes

Some code highlights:

```css
/* CSS Variables for consistent theming */
:root {
  --green: hsl(75, 94%, 57%);
  --white: hsl(0, 0%, 100%);
  --grey-700: hsl(0, 0%, 20%);
  --grey-800: hsl(0, 0%, 12%);
  --grey-900: hsl(0, 0%, 8%);
}
```

```html
<!-- Semantic HTML structure -->
<main role="main">
  <section class="card">
    <div class="image__wrapper">
      <img
        src="./assets/images/tasos.jpg"
        alt="Jessica Randall"
        class="card__image"
      />
    </div>
    <!-- ... -->
  </section>
</main>
```

## Author

- Frontend Mentor - [@tasosbeast](https://www.frontendmentor.io/profile/tasosbeast)
- Twitter - [@ANASTASIOSNTAN1](https://x.com/ANASTASIOSNTAN1)
- LinkedIn - [Tasos Ntantos](https://www.linkedin.com/in/tasos-ntantos-735b07100/)
