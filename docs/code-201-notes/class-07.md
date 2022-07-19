---
layout: default
title: Code 201 | Class 07
parent: Code 201 Notes
---

## Domain Modeling

### Explain why we need domain modeling

> Domain Modeling is understood as abstract modeling. a site model could be an illustration of the ideas or objects shown within the drawback domain. It additionally captures the apparent relationships among these objects.

[Geeks for Geeks Domain Modeling](https://www.geeksforgeeks.org/software-engineering-domain-modeling/)

### Why should tables not be used for page layouts?

* Layout tables reduce accessibility for visually impaired users: Screenreaders, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screenreaders' output will be confusing to their users.
* Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
* Tables are not automatically responsive: When you use proper layout containers (such as `<header>`, `<section>`, `<article>`, or `<div>`), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

[MDN HTML Tables](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

### List and describe 3 different semantic HTML elements used in an HTML `<table>`

* `<th>` Table header is used to identify what type of data will be in the subsequent rows / columns
* `<tr>` Table row is the parent of `<td>` and will contain all child `<td>` in a single row
* `<td>` Table data is used to identify data that will be rendered within the table
* `<colgroup>` Column group is the parent of `<col>` and will contain all child `<col>` in a single column
* `<col>` column will hold your column data

### What is a constructor and what are some advantages to using it?

A constructor can be thought of as a blank template that will allow you to pass in object information to quickly create ‘like’ objects with different attributes. You can use constructors to clean up repetitive function code.

### How does the term this differ when used in an object literal versus when used in a constructor?

In an object literal `this` refers to key values within the object. In a constructor, `this` refers to the corresponding keys of the object that it is passed.

### Explain prototypes and inheritance via an analogy from your previous work experience

A prototype is a property that every function in JavaScript has and a prototype allows us to share methods across all instances of a function

An analogy for prototype inheritance could be a library. Anyone can go into the library and check out a few books, but it would be impractical for one individual to try to check out every book from the library at once. Prototypes allow the developer to only call the methods that they need.

[Beginner’s guide to JavaScript’s Prototype](https://www.youtube.com/watch?v=XskMWBXNbp0&t)