---
layout: default
title: Code 201 | Class 03
parent: Code 201 Notes
---

## Ordered and Unordered lists

### When should you use an unordered list in your HTML document?

You would use an unordered list whenever you need to list items but their order is not important

### How do you change the bullet style of unordered list items?

Within the CSS styles file you can add attributes to your unordered list items.

List items can be formatted as:

* Circle

* Disc

* Square

### When should you use an ordered list vs an unordered list in your HTML document?

Unlike an unordered list, an ordered list is important when listed items need to be shown sequentially, like in a recipe or an instruction manual

### Describe two ways you can change the numbers on list items provided by an ordered list?

To change the initial number that the ordered list you can insert a `<ol start="x">` with x being the number or letter that you wish to begin your ordered list from

## The Box Model

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

> **The story of Mary Margin and Paul Padding:**  
>
> Paul Padding was thinking of Mary Margin again. “How does she do it?” Paul wondered as he paced across his room to his barred window.
>
> Paul reflected on his own situation, trapped, bounded by the borders of his home without a way to escape. Spending an eternity within the confines of his chambers. It wasn’t fair. Paul wanted nothing more than to break free and see the world from outside the walls of his room
>
> Then he saw something in the distance, or rather someone. It was her, the carefree spirit Mary Margin. Paul had seen Mary from time to time from a distance but could never meet face to face. The walls of his home created a border that he could never cross.
>
> Disheartened, Paul turned away from the window and slowly made his way out of his room. As Paul neared the center of his home he let his gaze fall upon his true treasure.
>
> “At least I’ll always have you” Paul said in a hushed tone  as a crooked smile crept over his face. “You’re my content and I’ll always be here for you”.

### List and describe the four parts of an HTML elements box as referred to by the box model

* Margin: This defines how much white space in relation to the HTML body that your element will have around it
* Border: This is connected to the HTML element and will display as a border surrounding the entire element
* Padding: This is white space within an element that will move interior content away from the outside edges of an element
* Content: This is the main body of content that is nested within your HTML element

## Learn JS

### Arrays. Operators and Expressions. Conditionals. Loops

What data types can you store inside of an Array?

* Strings
* Objects
* Numbers
* Other Arrays

### Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```JavaScript
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 ```

This is a valid array. To validate the array I used the command `Array.IsArray(people)`
after entering the array into my console. Below is a screenshot showing the Array.IsArray command returning true

![Screenshot of Array Validation](https://i.imgur.com/TeO5Hdg.jpg)

### List five shorthand operators for assignment in javascript and describe what they do

* `=` this operator will assign a value to a variable
* `+=` adds a value to a variable
* `-=` subtracts a value from a variable
* `*=` multiplies a variable
* `/=` divides a variable

### Read the code below and evaluate the last expression and explain what the result would be and why

 ```JavaScript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
(10+false(0)) + dog
  ```

The answer is 10dog. This is because expressions are evaluated left to right so the first thing to be evaluated would be 10+false. Because false evaluates to 0 in JavaScript this leaves us with 10+dog. This will return a value of 10dog

![Screenshot of console log](https://i.imgur.com/psbr1CJ.jpg)

### Describe a real world example of when a conditional statement should be used in a JavaScript program

Say for example you want to create a custom welcome to a user based off of their current local time. This can be achieved with conditional statements that would iterate through a block of code until it identifies a true condition.

### Give an example of when a Loop is useful in JavaScript

Loops are useful to automate tasks that would force an individual to make repeated inputs. Loops can continually run until the desired condition is met. This can also cause an issue with infinite loops if you’re not careful.
