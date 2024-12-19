
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
This is a landing page project. Built with html , css and javascript . 
### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![screenshot/desktop view.png](<screenshot/desktop view.png>)

![screenshot/mobile view.png](<screenshot/mobile view.png>)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid




### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```js
<script>
        document.addEventListener('DOMContentLoaded', function () {
        const menuIcons = document.querySelector('.menu-icons');
        const navLinks = document.querySelector('.nav-links');
        const authButtons = document.querySelector('auth-buttons');

        // Toggle menu on click
        menuIcons.addEventListener('click', function () {
            menuIcons.classList.toggle('active'); // Toggle icons
            navLinks.classList.toggle('active'); // Toggle menu visibility
            authButtons.classList.toggle('active');

        });
    });

    </script>
```
```css media queries
@media screen and (max-width: 375px) {
    .hamburger, .cancel {
                width: 30px;
                height: 30px;
                display: none;
            }
}
```



### Continued development

Navigation links for mobile . Found it difficult to implement the login and register 


### Useful resources

- w3Schools 


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)



## Acknowledgments
I would like to express my sincere gratitude to Miss Rhoda and Victor for their invaluable support and encouragement throughout the development of this project. Your guidance, insights, and assistance made a significant difference and truly helped me overcome challenges. Thank you for being a part of this journey with me.


