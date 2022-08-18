---
layout: default
title: Code 301 | Class 05
parent: Code 301 Notes
---

## Reading [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

### What is the single responsibility principle and how does it apply to components?

This is a principle stating that components should only do one thing. This keeps components simple enough to be easily modified without worrying about other code dependencies that you may be unintentionally breaking

### What does it mean to build a ‘static’ version of your application?

* This is building out components of your app but not adding any dynamic features. Each component would only contain a render element and is useful as a pseudo wireframe to build out the structure of you app while creating base components that can be fleshed out later

### Once you have a static application, what do you need to add?

* After the static app is built, you will need to identify what components wil need to be responsive to state

### What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props? If so, it probably isn’t state.

* Does it remain unchanged over time? If so, it probably isn’t state.

* Can you compute it based on any other state or props in your component? If so, it isn’t state.

How can you identify where state needs to live?

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.

* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

### What is a “higher-order function”?

* These are functions that take in other functions as arguments to operate on other functions

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

* For this example,

```JS
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
```

* Line 2 is declaring `m` as a function within the greaterThan function. It is evaluating a boolean to determine if m is greater than n, if it is, it will return truthy.

* This could also be written as

```JS
function(m){
  if(m > n) return true;
  else return false;
}
```

* If we wanted to use a more readable syntax over an arrow function

### Explain how either map or reduce operates, with regards to higher-order functions

* Map translates data from one type to another. Doesn’t necessarily mean that the data type changes - but you are changing from one form to another.

* Map will always return a collection the same size and order as its input. If you map an array of 3 things, you will get an array of 3 elements back, and the first item in the input will always correspond with the first item of the output.

* The result of map is always a new collection - the input collection is not modified.

* Map operations are inherently chainable. data.map(...).map(...).map(...) is a common pattern.
