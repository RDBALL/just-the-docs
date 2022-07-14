---
layout: default
title: Code 201 | Class 04
parent: Code 201 Notes
---

## Creating Hyperlinks

### To create a basic link, we wrap text or other content inside what element?

The `<a>` element is used when creating a link

### The href attribute contains what information?

Inside of an `<a>` element you will have href
`<a href=”https://www.ExampleSite.com”> Text for Hyperlink</a>`

### What are some ways we can ensure links on our pages are accessible to all readers?

* Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.
* Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different color and underlined (this convention generally shouldn't be broken, as users are used to it).
* Keep your link text as short as possible — this is helpful because screen readers need to interpret the entire link text.
* Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screen reader users, if there's a list of links out of context that are labeled "click here", "click here", "click here".

From [MDN Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

## Normal Flow CSS Layout: Positioning

### What is meant by “normal flow”?

This is referencing the basic structure that an html document will have with regard to CSS

### What are a few differences between block-level and inline elements?

|                           Block Elements| Inline Elements        |
|:-----------------------------------------------------------------|:-------------------------------------------------------------------------------|
|            Block elements always start from a new line.          |                   Inline elements never start from a new line.                 |
| Block elements cover space from left to right as far as it can go. | Inline elements only cover the space as bounded by the tags in the HTML element|
|             Block elements have top and bottom margins.          |                Inline elements don't have a top and bottom margin.             |
|           Examples of block elements - `<p>,<div>,<hr>` .        |                    Examples of inline elements - `<span>,<br>`                 |

[Scaler inline and Block Elements](https://www.scaler.com/topics/html/inline-and-block-elements/)

### ___ positioning is the default for every html element

* Static

### Name a few advantages to using absolute positioning on an element

* Elements that have absolute positioning are no longer controlled by the normal flow.
* Allows you to create isolated UI features that don’t interfere with the layout of other elements on the page
* This allows you to create an overlapping element if your design calls for one

### What is a key difference between fixed positioning and absolute positioning?

Fixed positioning is constrained relative to all other elements within the HTML document. Absolute positioning is not bound by those restraints.

Functions – Reusable Blocks of Code

Describe the difference between a function declaration and a function invocation.

* Function declaration: A function declaration tells the JavaScript engine about a function’s name, return type, and parameters.
* Function invocation: When a function has been declared, it can be used anytime inside a class or development scope whenever it’s been called/invoked.

[Better Programming Function Declaration v. Expression](https://betterprogramming.pub/newbie-js-function-declaration-vs-function-expression-a3ae67573270)

### What is the difference between a parameter and an argument?

A parameter within a function is the variable that will represent a value that will be processed. An argument is the value that you assign to the parameter..

### Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey

* Greater efficiency: An easy example of how Pair Programming could increase efficiency is if one partner excels at typing and syntax input. This would allow the other partner to focus on the broader concept of ensuring that the code being typed flowed with the overall design and met functionality requirements.
* Engaging collaboration: It is very rare to have two people working within a creative environment reach identical solutions to identical problems. It is always great to be able to explain your thought process to someone else and have them bounce back some ideas. Creativity thrives on collaboration.
