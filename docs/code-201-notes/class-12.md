---
layout: default
title: Code 201 | Class 12
parent: Code 201 Notes
---

## JavaScript Canvas

### What does the `<canvas>` allow a developer to achieve?

* `<canvas>` allows developers to draw 2d graphics using JavaScript. These drawings are contained within the `<canvas>` and must have both a `<height>` and `<width>` tag to specify the size of the `<canvas>`

### What is the importance of the closing `</canvas>` tag?

* Without closing the `</canvas>` element tag you will not be able to display content as part of the `</canvas>`  

### Explain what the getContext() method does

* The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it.

> The `<canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context

[MDN Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

## Chart.js Documentation

### What is Chart.js and how can it be brought into your project?

* Chart.js is a method of introducing dynamic charts into JavaScript. These charts are able to be brought into an application by including a `<script>` within a `<canvas>` element

```js
`<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>`
```

### List 3 different Chart types you can create using Chart.js

* Area Chart
* Bar Chart
* Bubble Chart
* Doughnut and Pie Chart
* Line Chart
* Mixed Chart
* Polar Area Chart
* Radar Chart
* Scatter Chart

## Easily Create Stunning Animated Charts with Chart.js

### What are some advantages to displaying data via a chart over a table?

* A chart can allow a user to easily identify the information that you are attempting to convey to them. It is easier to see extreme outliers on a visual chart versus looking at a table of numbers and other data.

### How could Chart.js aid your previously created applications visually?

* In the Salmon Cookies projects we could have included a chart that would visually display which stores sold the most cookies or other information that we would like to extrapolate from the data.
