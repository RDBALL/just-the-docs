---
layout: default
title: Code 201 | Class 13
parent: Code 201 Notes
---

## Local Storage and How To Use It On Websites

### Why would a developer use local storage for a web application?

* LocalStorage allows for basic persistence on your website. It's commonly used to keep data that would be convenient for the user to see even if the browser was refreshed. For example, many forms save a user's input in LocalStorage until it is submitted.
* 
* Static websites commonly use LocalStorage to store user preferences, like a UI theme. Without a web server and database to save a user preference, LocalStorage allows them to continue using your website with their customizations.

[stackabuse](https://stackabuse.com/storing-data-in-the-browser-with-localstorage/)

### What information should not be stored in local storage?
* Never store sensitive information in LocalStorage. This includes passwords, API Keys, authentication tokens like JWTs and financial information like credit card numbers, to name a few.

* Every JavaScript file that is loaded on your domain has access to LocalStorage. If malicious JavaScript code is added by you or your dependencies, they can retrieve user data or tokens you use to authenticate with APIs.

* Always keep sensitive data on the back-end.

[stackabuse](https://stackabuse.com/storing-data-in-the-browser-with-localstorage/)

### Local storage can store what type of data? How would you convert it to that type before storing?

* LocalStorage can only use strings for its keys and values. If we try to store any other type of data, it converts it to a string before storing it.

[stackabuse](https://stackabuse.com/storing-data-in-the-browser-with-localstorage/)
