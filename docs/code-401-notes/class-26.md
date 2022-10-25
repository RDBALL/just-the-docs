---
layout: default
title: Code 401 | Class 26
parent: Code 401 Notes
---

### Reading: useState() Hook

[Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

* What was the motivation for introducing Hooks?
  * This is a way to be able to use React state and lifecycle functions while inside of a function component.
* What changes are important regarding implementing Hooks versus Component Classes?
  * Hooks were implemented after around 5 years of development and there is no need to completely rewrite legacy code to be able to include hooks if your current component classes are able to reach full functionality within your application.
* Hooks allow you to reuse stateful logic without changing __________.
  * Hooks allow you to reuse stateful logic without changing your component hierarchy

[hooks api](https://reactjs.org/docs/hooks-overview.html)

* Name two rules imposed by React Hook usage.
  * Avoid calling hooks from within loops, conditions or nested functions
  * Avoid calling hooks from outside of React JS functions.
* How would you identify a custom Hook and why might you create one?
  * You can call a custom hook by prepending 'use' to the declared function component.
  * This can be useful if there is correlating data that you would like to extract.

[the state hook](https://reactjs.org/docs/hooks-state.html)

* What is a Hook?
  * A hook is a way to interact with react features and hook into them with a function
* When would I use the useState Hook?
  * You would use the useState hook when you need to access state. This is how to access state within a function rather than a class using this.state
* If you were to add React state to a function component by declaring a state variable:
  * What does calling useState do?
    * This declares a state variable that is able to preserve values between function calls
  * What do we pass to useState as an argument?
    * You pass the initial state to useState as an argument
  * What does useState return?
    * This returns the current state and a function that updates it.

Bookmark and Review

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)

* What are your learning goals after reading and reviewing the class README?

  * I would like to continue to expand my knowledge base with regards to hooks and when / how to implement them. I feel after I am able to practice more functional applications I will be able to more easily describe exactly when you would use a hook and more importantly why using a hook would be necessary or beneficial for different use cases.
