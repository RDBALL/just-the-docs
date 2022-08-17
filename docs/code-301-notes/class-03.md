---
layout: default
title: Code 301 | Class 03
parent: Code 301 Notes
---

# Readings: Passing Functions as Props

## Reading

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

### What does .map() return?

* .map() returns an array where a called function is passed to each (value, index) of the array

### If I want to loop through an array and display each value in JSX, how do I do that in React?

* Use .map() to loop through an array and then render a JSX element to pass in the new array created by .map();

### Each list item needs a unique ____

* Key

### What is the purpose of a key?

* Keys allow react to identify changes, additions or removals when applied to a items within an array

## The Spread Operator

### What is the spread operator?

* It takes an array and expands each array element into individuals elements

### List 4 things that the spread operator can do

* Adding an item to a list.
* Adding to state in React.
* Combining objects.
* Using Math functions

### Give an example of using the spread operator to combine two arrays

```JS
let fruits = ["apples", "bananas"];
let vegetables = ["corn", "carrots"];
let produce = [...fruits, ...vegetables];
//["apples","bananas","corn","carrots"]
```

### Give an example of using the spread operator to add a new item to an array

```JS
const zoo = ['🦊', '🐮'];
zoo.push('🐧');
console.log(zoo); // ['🦊', '🐮', '🐧']
```

[Append item to array](https://www.samanthaming.com/tidbits/87-5-ways-to-append-item-to-array/)

### Give an example of using the spread operator to combine two objects into one

```JS
let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};

let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

Output
{
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356',
    jobTitle: 'JavaScript Developer',
    location: 'USA'
}
```

[javaScript Merge Objects](https://www.javascripttutorial.net/object/javascript-merge-objects/)

## Videos

### [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

### In the video, what is the first step that the developer does to pass functions between components?

* They create the function wherever the state will change.

### In your own words, what does the increment function do?

* The increment function looks at the current value of the object that it is assigned to and increases its value by an assigned amount

### How can you pass a method from a parent component into a child component?

* You utilize props to pass methods from the parent component into a child component

### How does the child component invoke a method that was passed to it from a parent component?

* The child component will invoke the function defined in the parent component

### Bookmark and Review

[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
