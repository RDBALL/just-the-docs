---
layout: default
title: Code 102 | Read 06
parent: Code 102 Notes
nav_order: 7
---

# Read: 06 - Dynamic web pages with JavaScript

Javascript is a programming language that allows you to perform complex features on webpages

When a JavaScript file is added to an index directory it is able to load onto a webpage using a “script tag”

This script tag would look like `<script src=”index.js”/>` where index.js is the name of your JavaScript file

This would be loaded into the `<body>` of your index.html (like a CSS stylesheet link)

JS will wait to execute any code until it is “on your computer” within a browser. The browser engine will handle the JS file execution. A few client side modifications that JS can do include
* changing data or how the webpage is rendered  
* sending data from the user (like text field entry)
* retrieve more data from the server (following user inputs)

JS is considered to be an interpreted language meaning that it must be read line by line rather than compiled and sent as one data package.

Front end JS applications include
* react
* angular
* vue
* svelte

Back end JS environment node.js allows JS to write APIs, talk to databases and servers

 JS syntax contains “variables” that are either primitive or composite. Primitive variables are data that is not an object and has no methods or properties.
Primitive data types:
* string
* number
* bigint
* boolean
* undefined
* symbol
* null
 
From tutorialspoint a composite data type is: > A data type is known as a composite data type when it represents a number of similar or different data under a single declaration of variable i.e., a data type that has multiple values grouped together.
Examples of composite data include
* object
* array
* function

Helpful links
* [Tutorials Point](https://www.tutorialspoint.com/What-is-a-composite-data-type-i-e-object-in-JavaScript)
* [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Code maven input - output in JS](https://code-maven.com/input-output-in-plain-javascript)
* [w3schools JS walkthrough](https://www.w3schools.com/js/)
