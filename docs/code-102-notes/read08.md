---
layout: default
title: Code 102 | Read 08
parent: Code 102 Notes
nav_order: 9
---

# Read: 08 Operators and Loops

Operators in Javascript assign values, compare values, perform arithmetic operations and more!

The different classes of operators are:
Arithmetic: perform arithmetic between variables and values
Assignment: assign values to JS variables
String: + and = can be combined to add strings
Comparison: determine if two or more values are equal
Conditional: assign a value to a variable base on a condition
Logical: determines the logic between two variables
typeOf: when logged, will return with type of variable, object or function
Delete: deletes a property from an object

Loops mainly use a looping keyword, condition and a block. A loop in JS will continue to execute the body (block) for as long as the condition remains true.

The two loops we focused on were while loops and for loops.

A while loop executes the block again and again for as long as the resulting condition continues to meet the requirements of the loop. In order to have the block eventually stop repeating there must be code telling the loop when to stop. This will happen when the while loop iterates through the block but returns in a manner that does not meet the requirement of the loop. If this never took place a while loop would become an infinite loop.

Here is one example of a simple while loop

```javascript
let counter = 1;
  while (counter <= 10) {
    console.log(counter);
    counter = counter + 1;
  }
```

This loop will continuously iterate until “counter” is less than or equal to 10

For loops share the same purpose of while loops but they will not loop through the code block the same way that a while loop will. 

Here is how a for loop is structured

```javascript
for (statement 1; statement 2; statement 3) {
    // code block to be executed
}
```

* **Statement 1** is executed (one time) before the execution of the code block.
* **Statement 2** defines the condition for executing the code block.
* **Statement 3** is executed (every time) after the code block has been executed.

Here is an example of a for loop

```javascript
for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```

* Statement 1 sets a variable before the loop starts (let i = 0).

* Statement 2 defines the condition for the loop to run (i must be less than 5).

* Statement 3 increases a value (i++) each time the code block in the loop has been executed.

**Statement 1**   
Normally you will use statement 1 to initialize the variable used in the loop (let i = 0). This is not always the case, JavaScript doesn't care. Statement 1 is optional. You can initiate many values in statement 1 (separated by comma):

**Statement 2**  
Often statement 2 is used to evaluate the condition of the initial variable.
This is not always the case, JavaScript doesn't care. Statement 2 is also optional.
If statement 2 returns true, the loop will start over again, if it returns false, the loop will end.

**Statement 3**  
Often statement 3 increments the value of the initial variable.
This is not always the case, JavaScript doesn't care, and statement 3 is optional.
Statement 3 can do anything like negative increment (i--), positive increment (i = i + 15), or anything else.
Statement 3 can also be omitted (like when you increment your values inside the loop):


[w3schools](https://www.w3schools.com/js/js_loop_for.asp)  
[launch school](https://launchschool.com/books/javascript/read/loops_iterating#forloops)  
[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)