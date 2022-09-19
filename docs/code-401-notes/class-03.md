---
layout: default
title: Code 401 | Class 03
parent: Code 401 Notes
---

### Readings: Express REST API

### [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

### Classes are a template for creating ____

* Classes are a template for creating objects

### Can a class declaration be hoisted?

* A class must be defined before it is constructed. If a class is not defined before it is constructed it will throw an error when the dev attempts to compile the application.

### How would you describe a constructor and contextual “this” to a non-technical friend?

* A constructor can be seen as a "fill in the blank" template that can be filled in using the `this.<parameter>` syntax to apply a value to the various elements of a constructor

### [Using Express Routing](https://expressjs.com/en/guide/routing.html)

### Within Express, what does routing refer to?

* Routing refers to that way that an Express server handles URI endpoints that can be accessed by the user.

### What is the difference between a route path and a route method?

* Methods are attached to an instance of an express class.

* Routes are established to handle user input at defined web endpoints

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

* Whenever the route handler needs to bypass multiple callbacks you are able to use the `next` parameter to bypass unneeded callbacks

### [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

### What is an Express Router?

* Express Router is a class that helps us create router handlers or router objects

### How do we initialize express.Router() in an express server?

* You can call express.Router() using const or `let router = express.Router()'`

### What do we use route middleware for?

* This is used to perform functions before the request, response cycle is completed.
