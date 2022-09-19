---
layout: default
title: Code 401 | Class 02
parent: Code 401 Notes
---

### Readings: Express, NPM, TDD, CI/CD

### [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

### Explain middleware, answer as though I were a non-technical recruiter

* Middleware can be described as functions that can be incorporated into applications that allow specific functionality to be executed throughout the web request, response cycle.

### Express the most popular "__"

* Express is the most popular Node web framework.

### Express is “unopinionated.” What does that mean?

* Unopinionated web frameworks do not have strict rules on how they need to be compiled in order to reach functionality. This is in contrast to opinionated frameworks which are used to develop software within a specific domain that benefits more strict rules.

### What is a module and why is modularity useful to us as developers?

* A module is a separate library that can be pulled into your Node server. Modularity is useful as a developer so that you can break up your application into manageable chunks. This helps with ensuring that features can be continually updated while focusing on the compartmentalized components.

### [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

### What version of npm are you running on your machine?

* `npm version 8.19.1`

### What command would you type to install a library/package called ‘jshint’ into your node project?

* `npm i jshint`

### [What is TDD?](https://www.agilealliance.org/glossary/tdd/)

### Explain why tests are important. Please explain as though I were your non technical elder

* Tests are important to ensure proper application functionality.

### What are three expected benefits of testing

* Reduction in defect rates.

* Initial time taken to implement testing will reduce the time it takes to reach a production product.

* An increased internal coding quality.

### Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests

* Individual pitfalls:

  * Not running tests frequently enough

  * Running too many tests

* Team pitfalls:

  * Not every team member uses tests in the prescribed way

  * Test suite is never used.

### [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

### What are three benefits of Continuous Integration?

* Ensures each dev is working within the most up to date branch.

* Helps to catch bugs at their onset, versus waiting to merge later in development and having to run down bugs without knowing when they were introduced.

* Reduce merge conflicts.

### What is the difference between Continuous Delivery and Continuous Deployment?

* Continuous delivery is a process where an application is developed to be released at any time.

* Continuous deployment is a process where new features can be deployed immediately.

### Explain how GitHub fits into this process assuming the listener comes from a non-technical background

* GitHub provides a centralized location that allows software developers to contribute to a code repository by incorporating the CI/CD process.
