---
layout: default
title: Code 301 | Class 14
parent: Code 301 Notes
---

## CSS Transforms

### What does a CSS transform allow the developer to do to an element?

* This allows the developer to rotate, scale, skew or translate an element

### Provide an example of a transform and how you could see that being used on a website

* `transform: rotate();` will allow you to rotate an element along a central point.

```js
@keyframes rotating {
  0%  { transform: rotate(0deg);}
  100%{ transform: rotate(360deg);}
}
p{ animation: rotating 4s linear infinite;}
```

* The above code could be used to animate a pure css "loading" element when combined with JavaScript.

## CSS Transitions & Animations

### What does a CSS transition allow the developer to do to an element?

* transition-property: which properties to animate
* transition-duration: how long the animation lasts
* transition-timing-function: how the intermediate states are calculated
* transition-delay: to start the animation after a certain amount of time

### How does a CSS animation differ from a CSS transition?

* CSS transitions are just a way to animate CSS properties between a starting state, and an end state. Like the transition property, animation is a shorthand property for several others:
* name: the animation’s name
* duration: how long the transition lasts
* timing-function: how the intermediate states are calculated
* delay: to start the animation after a certain amount of time
* iteration-count: how many times the animation should be performed
* direction: if the animation should be reversed or not
* fill-mode: what styles are applied before the animation starts and after it ends

### What are some benefits to using CSS transitions on websites?

* They provide a dynamic and reactive user experience

### How this topic fit in with your long-term goals?

* I believe that implementing transitions and animations could go a long way into creating fun and interactive apps when used in combination with JavaScript.
