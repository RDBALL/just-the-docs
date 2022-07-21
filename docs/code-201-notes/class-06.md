---
layout: default
title: Code 201 | Class 06
parent: Code 201 Notes
---

## JavaScript Object Basics

### How would you describe an object to a non-technical friend you grew up with?

An object can be seen as a container. You can look through the contents of this container. You can dump the contents of this container out. You can add new items to the container. You can even put other containers within this container.

### What are some advantages to creating object literals?

Object literals can be beneficial if you are trying to mitigate potential variable naming conflicts by encapsulating related code inside of an object literal.

### How do objects differ from arrays?

One thing to keep in mind is that technically every JavaScript array is an object but the opposite is not true.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

**Dot notation:**

* Property identifies can only be alphanumeric.
* Property identifiers cannot start with a number.
* Property identifiers cannot contain variables.
* OK — `obj.prop_1, obj.prop$`
* Not OK — `obj.1prop, obj.prop name`

**Bracket notation:**

* Property identifiers have to be a String or a variable that references a String.
* It is okay to use variables, spaces, and Strings that start with numbers
* OK — `obj["1prop"]`, `obj["prop name"]`

[Codeburst Dot v. Bracket Notation](https://codeburst.io/javascript-quickie-dot-notation-vs-bracket-notation-333641c0f781)

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

The `this` keyword when included within an object will refer to the object that it is encapsulated in. Using `this` inside of an object allows you to reference identified variables within the object. For example if you had the variable `name` referenced outside of the object, the `console.log` command would reference the `name` global variable rather than the contained `name` variable. If `this` is used outside of an object then it will be referencing the global window.

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

## Introduction To The DOM

### What is the DOM?

The Document Object Model (DOM) defines the logical structure of documents and the way a document is accessed and manipulated

### Briefly describe the relationship between the DOM and JavaScript

The previous short example, like nearly all examples, is JavaScript. That is to say, it is written in JavaScript, but uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

[MDN DOM and JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
