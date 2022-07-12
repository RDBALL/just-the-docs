---
layout: default
title: Code 201 | Class 01
parent: Code 201 Notes
---

# Getting Started

### Compose a short poem describing how HTTP sends data between computers.

A Haiku following the 5-7-5 format:

> *user types cat pic  
data sent to server cloud  
cat picture sent back*

### Describe how HTML, CSS, and JavaScript files are “parsed” in the browser.

When a person establishes a connection to a website their browser needs to know exactly what type of information to return as a readable webpage. To make this happen the browser will first look for an HTML document that will contain the building block instructions for how the website should be structured.

While parsing the HTML page the browser will take note of any tags that would instruct the browser to look for identified CSS styling or JavaScript code to be executed. These are identified in HTML as either a `<link>` tag for linking a stylesheet to the html document or a `<script>` tag that causes JavaScript to be called or invoked.

When the HTML document has been read by the browser, identified stylesheets were applied and any JavaScript is  executed the browser will then fully display the website as it is intended to be viewed.

### How can you find images to add to a Website?

* Images can be found on stock image sites that will either list the image as free to use (with commercial restrictions) or available for purchase. 

* You can search through google and use google's search tools to explicitly return image results that hold a creative common license. This type of license may still require attribution. 
 
* You can always take your own pictures or create your own graphic designs!


### How do you create a String vs a Number in JavaScript?

A string in JavaScript is depicted as a word encapsulated in quotation marks.
Example: `'This is a string'`

A number in JavaScript is a numeral not inside of quotation marks.
Example: `9` is a number

### What is a Variable and why are they important in JavaScript?

Variables in JavaScript are similar to variables in mathematics. They allow the coder to assign certain values to specific variables. You can assign strings, numbers, arrays, booleans, and objects to variables to enable dynamic JavaScript content to be delivered to the user.

Answers sourced from [Mozilla Developer Getting Started with the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)


## Introduction to HTML

### What is an HTML attribute?

An attribute is HTML that is not visually displayed on a rendered webpage but contained inside of various HTML tags. Attributes can contain information such as pointing to a URL, adding a class or adding an id to a specific portion of HTML to be referenced in a connected stylesheet.

### Describe the Anatomy of an HTML element.

An HTML element will begin with an opening `<tag>` followed by any necessary attributes before listing the content to be displayed. The element is then closed with a closing `</tag>`


### What is the Difference between `<article>` and `<section>` element tags?

Articles are used when the content within the `<article>` tag is meant to be able to be shown on its own or in its own context. A `<section>` is used when a page needs to be divided in a way that would benefit from the inclusion of multiple sections. An example for the inclusion of a `<section>` tag could be to identify multiple sections of one inclusive piece of content. In this example there would be `<article>` tags within the `<section>` tags.

### What Elements does a “typical” website include?

From Mozilla Developer a typical website includes:

* Header
* Navigation bar
* Main content
* Sidebar
* Footer

### How does metadata influence Search Engine Optimization?

**From MDN**

> Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines (such activities are termed Search Engine Optimization, or SEO.)

### How is the <meta> HTML tag used when specifying metadata?

The `<meta>` tag is contained within the head of your HTML document and is used for a variety of functions. Two examples that the `<meta>`  tag can be used for:

* `<meta charset="UTF-8">` specifies character encoding for the HTML document
* `<meta name=”author” content=”Name”>` holds the page authors name using the `<content>` attribute

Sources:

[Mozilla Developer HTML and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Mozilla Developer Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)


## How to start to design a Website

### What is the first step to designing a Website?

The first step of designing a website is to identify what type of content you would like to display and create a wireframe diagram showing the initial structure of how you would like the website to be rendered.

### What is the most important question to answer when designing a Website?

The most important question to answer is to figure out what you are actually trying to accomplish. This will allow you to backwards plan to ensure that your desired endstate will be met.

## Semantics

### Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

An `<h1>` tag is specifically designed to help structure your HTML in an easy to read / digest manner. Recreating the look of an `<h1>` tag using a `<span>` tag can be done but it does not conform to a well structured HTML document.

### What are the benefits of using semantic tags in our HTML?

Semantic tags allow HTML to be more easily read as the tags will generally explain in simple words what their exact purpose is within the HTML document.

## What is JavaScript?

### Describe 2 things that require JavaScript in the Browser.

Any element that requires content to be dynamically generated. Two examples are displaying an image based off of user input or implementing a prompt that will then call additional functions following user input.

### How can you add JavaScript to an HTML document?

You can add JavaScript to an HTML document by including a `<script>` tag within the HTML document where you want a JavaScript function to be called.
