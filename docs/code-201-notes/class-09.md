---
layout: default
title: Code 201 | Class 09
parent: Code 201 Notes
---

## Your first Web Form. How To Structure A Web Form.

### Why are forms so important in web development?

>Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).
>
>A web form's HTML is made up of one or more form controls (sometimes called widgets), plus some additional elements to help structure the overall form — they are often referred to as HTML forms. The controls can be single or multi-line text fields, dropdown boxes, buttons, checkboxes, or radio buttons, and are mostly created using the `<input>` element, although there are some other elements to learn about too.
>
>Form controls can also be programmed to enforce specific formats or values to be entered (form validation), and paired with text labels that describe their purpose to both sighted and visually impaired users.

[MDN Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

### When designing a form, what are some key things to keep in mind when it comes to user experience?

* Keep the form simple
* Keep the form short
* Understand exactly what you are requiring from the user

### List 5 form elements and explain their importance

* `form` - this element defines a form and is a container
	* the `form` element will contain an action attribute that will link to where forms will be stored
	* the `form` element also contains a method attribute defines the HTTP method to sent the data with
* `label` - this is the text that your form input fields will inherit
* `input` - this will allow you to define an input such as name or email
* `textarea` - allows users to enter plain text such as comments
* `button` - This will place a button for the user to submit their form

## Introduction To Events

### How would you describe events to a non-technical friend?

Events can be thought of as an action that causes a reaction. These actions can either be active or passive depending on what they are “listening” for.

### When using the addEventListener() method, what 2 arguments will you need to provide?

* The name of the event
* A function to handle the event

### Describe the event object. Why is the target within the event object useful?

The event object has properties that describe the event interaction. The event target is the inner most nested element that was targeted by the event (e.g., the element that was clicked).


### What is the difference between event bubbling and event capturing?

* **In the capturing phase:**

* The browser checks to see if the element's outer-most ancestor `(<html>)` has a click event handler registered on it for the capturing phase, and runs it if so.

* Then it moves on to the next element inside `<html>` and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.

* **In the bubbling phase, the exact opposite of the capturing phase occurs:**

* The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so.

* Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the `<html>`element.
