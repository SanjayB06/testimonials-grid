# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](images/screenshot.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This exercise was an excellent way for me to learn more about CSS grid and especially grid template areas, which made responsive design significantly simpler. All that was needed within the media query was the grid template areas property defined for the parent element and then assigning areas to each child.

```css
@media (min-width:800px) {
    .container {
        grid-template-areas: 
        "Daniel Daniel Daniel Jonathan Kira"
        "Jeanette Patrick Patrick Patrick Kira";
    }
    #Daniel {
        grid-area: Daniel
    }
    #Jonathan {
        grid-area: Jonathan
    }
    #Kira {
        grid-area: Kira
    }
    #Jeanette {
        grid-area: Jeanette;
    }
    #Patrick {
        grid-area: Patrick
    }
}
```


### Useful resources

- [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/#grid-properties) - I used this resource for another FrontEndMentor project and it continues to be useful, providing a quick reference for grid property usages. 


## Author

- Frontend Mentor - [@SanjayB06](https://www.frontendmentor.io/profile/SanjayB06)

