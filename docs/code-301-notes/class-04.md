---
layout: default
title: Code 301 | Class 04
parent: Code 301 Notes
---

# Readings: React and Forms

## Reading [React Docs - Forms](https://reactjs.org/docs/forms.html)

### What is a ‘Controlled Component’?

* A controlled component is a component whose data is handled by state

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

* Updating the user response on every keystroke will allow their input to be written into state globally and can bring in global functions

### How do we target what the user is entering if we have an event handler on an input field?

* Use the tag `<input type="text" value={this.state.value} onChange={this.handleChange} />` within the element that you would like to have capture and update following user input

## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

### Why would we use a ternary operator?

* Ternary operators allow the dev to reduce multiple lines of code that would use an `else` statement into a more streamlined syntax

### Rewrite the following statement using a ternary statement:

```JS
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

**Refactor**

```JS
// if(x===y){
//   console.log(true);
// } else {
//   console.log(false);
// }

let x = 5
let y = 3

let result = x===y ? true : false
console.log(result);
// output: false
```

**Bookmark and Review**

[React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)

[React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
