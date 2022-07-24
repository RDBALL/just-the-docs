---
layout: default
title: Code 201 | Class 10
parent: Code 201 Notes
---

## What Went Wrong? Troubleshooting JavaScript

### Name some key differences between a Syntax Error and a Logic Error

* Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!

* Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

[MDN Troubleshooting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

### List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them

* Undefined function - I had declared a function and when I went to call it, I received an undefined error. What had happened is that I had failed to append a semicolon to one line within the function code. The function worked as expected after fixing that error.

* Infinite loop - When creating a while loop I accidentally entered `=` rather than `===` when wanting to return a true value. This caused the while loop to always result in true and caused an infinite loop. It was an easy fix to add the necessary operators.

### How will this topic continue to influence your long term goals?

I feel like as you progress through any career it is only natural to try to continuously develop yourself by learning new tools or new concepts. As you learn new skills you will inherently run into issues or road-blocks and having the necessary skills to "debug" your predicament will be paramount to your success.

### The JavaScript Debugger

## How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

The debugger tool is a tool built into most browsers that will allow you to identify and trace any errors that occur when trying to render a webpage.

### Define what a breakpoint is

* In the debugger window, you can set breakpoints in the JavaScript code.

* At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

* After examining values, you can resume the execution of code (typically with a play button).

[w3 debugging](https://www.w3schools.com/js/js_debugging.asp)

### What is the call stack?

* The Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint.
