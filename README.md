# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/product-preview-card-component-YDvCUoaNJF](https://www.frontendmentor.io/solutions/product-preview-card-component-YDvCUoaNJF)
- Live Site URL: [https://lloydb95.github.io/Product-Preview-Card-training/](https://lloydb95.github.io/Product-Preview-Card-training/)

## My process

### Built with

- Semantic HTML5 markup
- Tailwind CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

As this was my first CSS Challenge, I have learnt many HTML and CSS processes, mainly Tailwind. I have learnt how to use Tailwind classes to format the component in a way that reduces excess code than is needed.

In this code snippet below, I have used the **grid** and **grid-cols** function to make two seperate columns to seperate and align the image with the text/rest of the body. Also, adding **md:block** means it will block this is image from showing when viewing from a mobile device while **md-hidden** blocks the mobile image from being shown while viewing it from a desktop.

```html
<div class="grid md:grid-cols-2 bg-white rounded-lg overflow-hidden max-w-2xl">
    <div>
      <img src="./images/image-product-desktop.jpg" class="hidden md:block" alt="Perfume bottle resting near foliage">
      <img src="./images/image-product-mobile.jpg" class="md:hidden" alt="Perfume bottle resting near foliage">

    </div>
```

### Continued development

I will continue to develop my skills within Tailwind to better utilise the class system, this will allow me to create elements more efficiently.

### Useful resources

- [Tailwind CSS - Grid Columns](https://tailwindcss.com/docs/grid-template-columns) - This was a very helpful resource as it allowed me to create two seperate columns within this component which heavily cut down on adjusting the image and text.
- [Tailwind CSS - Flex](https://tailwindcss.com/docs/flex) - I have used this resource extensively to allow for Tailwind to make website components more flexible. This also allows for content and items to be justified, making aligning content far easier.

## Author

- Frontend Mentor - [@LloydB95](https://www.frontendmentor.io/profile/LloydB95)

## Acknowledgments

I have had help from a colleague with extensive knowledge on the subject.
