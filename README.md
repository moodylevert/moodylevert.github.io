# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

I was tasked with creating a QR code component for a website, using the HTML and CSS and making it look as close to the design example provided as possible. 

### Screenshot

![main/solution_screenshot.png]

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Live Site URL: [https://moodylevert.github.io/]

## My process

My process was strictly a mobile first approach. I made sure to write the HTML semantically and from there, just making sure that all of the required images and links were included. There after I included the styles that were provided in the guide, such as font size and colors. After that, I then created a container for the qr code and in css added code to make sure that it was aligned horizontally. In addition, I added a class selector to the text so that I could make changes to the text so I can include a media query to add some level of responsiveness. 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I learned the power of relative sizing options in css when trying to manipulate the text in the realm of responsiveness. Even though there weren't alot of screens at the resolution of the query, it was still good to see it at work. 

```css
@media (max-width: 340px) {
    .qr-container{
        min-width: 175px;    
    }
    .header{
        font-size: 1vh;
    }
    #pgh{
        font-size: 12px;
    }
}
```

### Continued development

In the future, I might experiment with using grid or flex-box for this design, to be able to better align and manipulate the placement of the container. 

## Author

- Frontend Mentor - [@moodylevert](https://www.frontendmentor.io/profile/moodylevert)


