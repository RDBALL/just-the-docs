---
layout: default
title: Code 201 | Class 02
parent: Code 201 Notes
---
# Intro to HTML continued

### Why is it important to use semantic elements in HTML?

Your browser utilizes semantics within HTML documents to understand how to correctly structure a webpage. Semantic elements also help developers and users understand coding syntax utilizing common terminology.

### How many levels of headings are there in HTML?

There are 6 levels of HTML heading tags
# `<h1>`
## `<h2>`
### `<h3>`
#### `<h4>`
##### `<h5>`
###### `<h6>`


### What are some uses for the `<sup>` and `<sub>` elements?

* The tag `<sup>` is utilized for superscript within strings such as the date November 25<sup>th</sup>
* The `<sub>` tag is used for subscript text within strings for uses such as creating footnotes when citing a source in writing.
> "The Nicholas Cage film ‘The Rock’ is a cinematic masterpiece<sub>1</sub>"  
> ##### <sub>1</sub> Robert Ball, Code 201 class 02, 2022

### When using the `<abbr>` element, what attributes must be added to provide the full expansion of the term?

Using the `<abbr>` tag allows you to display an abbreviation that includes a hover over function to display a title that is assigned to the abbreviation.

<p>Here is an example of what <abbr title="Hyper Text Markup Language">HTML</abbr> (hover over the HTML abbreviation) would look like when a title to the abbreviation is included</p>

code below:

``` html
<p>Here is an example of what <abbr title="Hyper Text Markup Language">HTML</abbr> would look like when a title to the abbreviation is included</p>
```
## How is CSS structured

### What are ways we can apply CSS to our HTML?

CSS can be applied to HTML in three different ways.
* The most direct css implementation is “inline” styling. This type of styling will be placed directly into the line of HTML that you are utilizing CSS to style. It is best practice to avoid this style of CSS implementation due to the non-universal, singular nature of inline styling.
* Second order of precedence is an internal stylesheet. This is CSS that is formatted within the head of your html document that holds the styling that will be applied to your HTML. 
* The third and most universal way of utilizing CSS with HTML is by using an external stylesheet. This is a secondary CSS file that is located within the root directory along with your HTML file. This stylesheet is able to be linked to your html document with a link tag within the head of your document.

### *Answer for the block of code below*
```CSS
  h2 {
     color: black;
     padding: 5px;
   }
```
### What is representing the selector?

* The h2 HTML `<tag>` is being selected for editing in this example

### Which components are the CSS declarations?

* Both the `color` and the `padding` are shown as declarations to be identified

### Which components are considered properties?

* The properties of this CSS style code are `black` and `5px`
Continuing JavaScript fundamentals

### What data type is a sequence of text enclosed in single quote marks?

Strings are encapsulated within single quotes marks

### List 4 types of JavaScript operators.

JavaScript includes various categories of operators:

* Arithmetic operators 

* Comparison operators

* Logical operators

* Assignment operators

* Conditional operators

These operators help to build dynamic features within your page

### Describe a real world Problem you could solve with a Function.

You could use a function to put a basic block / restriction onto a webpage by having a user verify their date of birth. If the user's date of birth does not equal whatever the age limit is, an else if function could redirect them from your webpage. If their date of birth does meet the set age limit they would be allowed to proceed to the main webpage.

You could also implement a function that could serve as an arithmetic calculator

## Conditionals in your JavaScript

### An if statement checks a __ and if it evaluates to ___, then the code block will execute.

An if statement will check a condition to determine if the condition is true. Weather the condition is true or false is identified following the execution of code that the condition is testing. If the code evaluates to true then the condition will execute.

### What is the use of an else if?

An else if will allow the function to be dynamic. It can display one thing if the code is identified as true or display something entirely different if the code is evaluated as being false.

### List 3 different types of comparison operators.

| Operator | Name                     | Purpose                                                                  | Example      |   |   |   |   |   |   |
|----------|--------------------------|--------------------------------------------------------------------------|--------------|---|---|---|---|---|---|
| ===      | Strict equality          | Tests whether the left and right values are identical to one another     | 5 === 2 + 4  |   |   |   |   |   |   |
| !==      | Strict-non-equality      | Tests whether the left and right values are not identical to one another | 5 !== 2 + 3  |   |   |   |   |   |   |
| <        | Less than                | Tests whether the left value is smaller than the right one.              | 10 < 6       |   |   |   |   |   |   |
| >        | Greater than             | Tests whether the left value is greater than the right one.              | 10 > 20      |   |   |   |   |   |   |
| <=       | Less than or equal to    | Tests whether the left value is smaller than or equal to the right one.  | 3 <= 2       |   |   |   |   |   |   |
| >=       | Greater than or equal to | Tests whether the left value is greater than or equal to the right one.  | 5 >= 4       |   |   |   |   |   |   |
|          |                          |                                    



[MDN Comparison Operators](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Math#comparison_operators)


### What is the difference between the logical operator && and ||?

The operator `&&` is used to identify multiple parameters that are either all true or all false. This operator will return true only if all parameters are met. The `||` operator is used in the case of needing an “or” statement to evaluate as true or false. This will take multiple parameters and will return a value of true if either parameter evaluates as “true”.
