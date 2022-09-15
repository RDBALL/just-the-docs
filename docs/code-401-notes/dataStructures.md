---
layout: default
title: Code 401 | Data Structures
parent: Code 401 Notes
---

### Data Structures and Algorithms

### What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

* You must first attempt to analyze and understand the problem that you are trying to solve. This will allow you to determine the basic operations that must be supported by your solution. What are you going to be doing with the data?

* You also need to consider if there is any emphasis on speed in relation to query results or data insertion, updating or deleting.

### Common JavaScript Data Structures and their descriptions

* Stack - follows the first in, last out principle. Data that is inserted into a stack can be immediately accessed as it is the current "top level" of the stack.

* Queue - follows the first in, first out principle where data is inserted into the "back" of the queue and data is retrieved from the "front" of the queue.

* Linked List - this is a chained data structure made up of nodes. These nodes consist of two pieces of information, the data of the node and the pointer to the next node. Linked lists will generally result in faster speeds with a smaller memory overhead.

* Set - This is a collection of defined objects. A set does not allow repeating elements and the set itself is not indexed.

* Hash Table - these have a key-value data structure. This promotes very fast transmission speed as a key is only necessary to find the adjoining data.

* Tree - this is non-linear data and is efficient during insert and search operations.

* Graph - these are a set of nodes with links. These are used inside of navigation apps or when an app wants to be able to give the user recommendations

> [Javascript Data Structures](https://builtin.com/software-engineering-perspectives/javascript-data-structures)

### How can we ensure that we’ll avoid an infinite recursive call stack?

* There are four methods that you can use to avoid a stack overflow when dealing with recursion

* `setTimeout` - this will allow you to declare a set amount of time that a function will run when it is invoked.

* `setImmediate` - similar to `setTimeout`, this method is not scheduled and will execute immediately. This method executes faster than setTimeout due to it not being scheduled

* `nextTick` - this method executes the function at the first opportunity, bypassing the event message queue.

* Loops - instead of calling functions directly, the main loop can call a function through a variable. The function variable is set by each function call, and it becomes the responsibility of the loop construct to invoke each function

> [Avoiding Stack Overflow in Javascript](https://levelup.gitconnected.com/the-call-stack-is-not-an-infinite-resource-d530df0041bc)
