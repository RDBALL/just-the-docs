---
layout: default
title: Code 301 | Class 12
parent: Code 301 Notes
---

### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

### In your own words, describe what each group of status code represents:

* 100’s = Informal codes that will tell the user the head has been received but not the body
* 200’s = Theses are success messages
* 300’s = Theses are redirection codes that inform the user that the requested resource is not available
* 400’s = Theses are client error codes such as 404
* 500’s = Theses are codes that will be displayed by the server

### What is a status code 202?

* 202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

### What is a status code 308?

* 308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

### What code would you use if an update didn’t return data to a client?

* 204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.

### What code would you use if a resource used to exist but no longer does?

* 307 Temporary Redirect - This is the right code if the resource could be available on a different URL in the future, but we want the current endpoint to control where the client is redirected to. This status code will let the client come back to the current URL for every request.

* 308 Permanent Redirect - This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.



### What is the ‘Forbidden’ status code?

* 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


[Build A REST API With Node.js, Express, & MongoDB](https://www.youtube.com/watch?v=fgTGADljAeg)

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* So that we can access the MongoDB without having our user:pass exposed

### What is middleware?

* Middleware is code that runs when the server receives a request but before it is passed to your defined routes

### What does app.use(express.json()) do?

* Allows the server to accept JSON as a body rather than a post or get element

### What does the /:id mean in a route?

* That is a parameter that allows you to retrieve whatever a user inputs following the `/:id` tag

### What is the difference between PUT and PATCH?

* PUT is a method of modifying a resource where the client sends data that updates the entire resource . 

* PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

### How do you make a default value in a schema?

* you use the keyword 'default: 'value' within your schema

### What does a 500 error status code mean?

* The HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request

### What is the difference between a status 200 and a status 201?

* The 200 status means that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).
