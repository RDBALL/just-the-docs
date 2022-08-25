---
layout: default
title: Code 301 | Class 09
parent: Code 301 Notes
---

## Reading [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

### What is functional programming?

* Generally, functional programming means using functions to the best effect for creating clean and maintainable software

### What is a pure function and how do we know if something is a pure function?

* The ideal in functional programming is what is known as pure functions. A pure function is one whose results are dependent only upon the input parameters, and whose operation initiates no side effect, that is, makes no external impact besides the return value.

[infoworld](https://www.infoworld.com/article/3613715/what-is-functional-programming-a-practical-guide.html)

### What are the benefits of a pure function?

* Simple Architecture

* Reduced to only arguments and it's returned value

### What is immutability?

* Not modifying the input outside of the function

### What is Referential transparency?

* Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program. As a result, methods should always return the same value for the given argument without any side effects.

[techaffinity](https://techaffinity.com/blog/functional-programming-in-javascript-part1/)

## Videos [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

### What is a module?

* a module is a file that contains certain functionality that is related.

### What does the word ‘require’ do?

* require forces node to pull in certain files based off the passed path

### How do we bring another module into the file we are working in?

* require('./path to module');

### What do we have to do to make a module available?

* within the module you must append module.exports = "function to be made available"
