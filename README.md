# Frontend Mentor - Bookmark landing page solution

This is a solution to the [Bookmark landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bookmark-landing-page-5d0b588a9edda32581d29158). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

This is a practice project which is given from Frontend Mentor.This challenge was so tough for me because this was the first time when i was building this kind of huge project. After all I am able to do it.Of course it would be better more but as i mention this is first time for me.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- See the Accordion section.(at first the contents is hidden but when the user click the header section the content will be appear)
- See the Features section.(Click the tab button and you will be see various content depends on which button you clicked)
- Receive an error message when the newsletter form is submitted if:
  - The input field is empty
  - The email address is not formatted correctly

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [(https://github.com/nasim67reja/Bookmark.github.io)]
- Live Site URL: [https://nasim67reja.github.io/Bookmark.github.io/]

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I have learned so much thing by doing this project. Now I'm understand gradually why the famous developers tell to foucs on building project. I want to mention those part which one's was frustating for me before this project but now I am able to understand those things and how they works such as svg.

- 1 . svg was so frustating for me specially these things how the viewox work why inline svg is better when classes and id works with svg. But a playlist on you tube which is cover the svg was very helpful for me . I learnt a lot about svg from the you tube playlist.

- 2 . overflow-x: hidden: - when I was building the resposive part of navigation it was so tough part for me and so crucial also. overflow-x propertry was helping me there and it was the first when i used this css property

```css
html {
  overflow-x: hidden;
}
.icon,
.social-icon {
  transition: all 0.3s;
}
/* understand this trick */
.icon:hover .social-icon,
.icon:hover {
  cursor: pointer;
  fill: var(--soft-red);
}
/* Hidden element without display none. because display none don't accept the property transition */
.s {
  /* Hide navigation */
  /* Allows NO transitions at all */
  /* display: none; */

  /* 1) Hide it visually */
  opacity: 0;

  /* 2) Make it unaccessible to mouse and keyboard */
  pointer-events: none;

  /* 3) Hide it from screen readers */
  visibility: hidden;
}
```

- 3 . the blue bacground part is special for me . I have learnt a lot by making this type of background

### Continued development

For future Project I want to focus on the form. I think I need to improve my skills about making form and also wanted to make this kind of project.

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=ZJSCl6XEdP8) - The svg series of Kevin Powell is very good playlist. His clean explaination clear my doubt about svg
- [Example resource 2](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/) - I also mention it here this playlist is like bibel for me.

## Author

- Website - [Nasim Reja](https://www.your-site.com)
- Frontend Mentor - [@nasim67reja](https://www.frontendmentor.io/profile/@nasim67reja)
- Twitter - [@Nasimreja97](https://www.twitter.com/@Nasimreja97)
