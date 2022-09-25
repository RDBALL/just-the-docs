---
layout: default
title: Code 401 | Class 06
parent: Code 401 Notes
---

## Readings: Authentication

### [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

* Explain to a non-technical friend how you would safely hash and store a password.
  * In order to hash and store a password you first need to decide what type of hashing methods you want to incorporate. When you've made your choice, you enable the correct dependencies and then have plaintext passwords put through the chosen hash method and then are stored as a hash. This means that your plain text password is never stored in the database as a visible password.
* What is Bcrypt?
  * Bcrypt is a hashing algorithm that is slow by design
* Why might you use something like Bcrypt?
  * You could implement bcrypt when you need to require salting your hashes. It also provides an increase in brute-force security.

### [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

* What is Basic Authentication?
  * Basic authentication is used in the process of creating usernames and passwords with basic security needs of matching a user to a password.
* What properties are necessary in the header of a Basic Auth request?
  * Authorization: Basic `<credentials>`

* How are username:password in Basic Auth encoded?
  * For "Basic" authentication the credentials are constructed by first combining the username and the password with a colon (aladdin:opensesame), and then by encoding the resulting string in base64 (YWxhZGRpbjpvcGVuc2VzYW1l)

### [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

* Define the authentication process to a non-technical recruiter.
  * The basics behind an authentication requests is that the server takes the user input and checks against known inputs stored in the server database. The authentication happens during the data request sent from the user to the server, and back from the server to the user.
* How should your error messaging respond (both HTTP and HTML)? Why?
  * The error message should respond with a generic error. The error shouldnt signify exactly what the error was in order to promote better infosec.
* Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

### Bookmark and Review

### [bcrypt docs](https://www.npmjs.com/package/bcrypt)
