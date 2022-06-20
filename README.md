# Frontend Mentor - NFT preview card component solution

This is a Design for [animation; learning how to use animation for art and web design expecially on the use of animation properties]. Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Animation
- Position in CSS


### What I learned

transform
The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS, transform properties include:

transform: matrix(1.0, 2.0, 3.0, 4.0, 5.0, 6.0);
transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
transform: perspective(17px);
transform: rotate(0.5turn);
transform: rotate3d(1, 2.0, 3.0, 10deg);
transform: rotateX(10deg);
transform: rotateY(10deg);
transform: rotateZ(10deg);
transform: translate(12px, 50%);
transform: translate3d(12px, 50%, 3em);
transform: translateX(2em);
transform: translateY(3in);
transform: translateZ(2px);
transform: scale(2, 0.5);
transform: scale3d(2.5, 1.2, 0.3);
transform: scaleX(2);
transform: scaleY(0.5);
transform: scaleZ(0.3);
transform: skew(30deg, 20deg);
transform: skewX(30deg);
transform: skewY(1.07rad);

Well dont bother in trying to know all atleat my self got familiar with the most properties i feel will be relvevant in design accessible site; rotate, translate, and scale.

Using CSS animations
CSS animations make it possible to animate transitions from one CSS style configuration to another. Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation's style, as well as possible intermediate waypoints.
You would find my used in the code snipet below beside it the primary purpose of this design to get hand on animation 

Using media queries
Media queries are useful when you want to modify your site or app depending on a device's general type (such as print vs. screen) or specific characteristics and parameters (such as screen resolution or browser viewport width).

To conditionally apply styles with the CSS @media and @import at-rules.
as seen in the code snipet below;


```
.animeTyre {
  
    transform: translateX(-50%);
    
}
```
```
.animeRoad {
    background-repeat: repeat-x;
    animation: road 10s linear infinite;
}
```
```
@keyframes road {
    100% {
        transform: translateX(-3200px);
    }
}
```
```
media (min-width:320px) and (max-width: 768px){
    .animeMotor {
        width: 250px;
        bottom: 127px;
    }
```
    


### Continued development

- Animation 
- Transform 
- Mediaqueries


### Useful resources

- [mozilla fire fox 1](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [mozilla fire fox resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.



## Author

- Github - [Jasper-Ik](https://github.com/Jasper-Ik)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Jasper-Ik)
- Twitter - [@yJ_sperIk](https://www.twitter.com/J_sperIk)



## Acknowledgments

Easy tutorial