---
layout: default
title: Code 401 | Class 07
parent: Code 401 Notes
---

## Reading: Bearer Authorization

### [Intro to JWT](https://jwt.io/introduction/)

* What is a JSON Web Token (JWT)?
A self-contained way for securely transmitting information between parties as a JSON object
* When should we use JSON Web Tokens?
JWTs can be used for authorization and information exchange
* Claims are expected in which structural component of a JWT?
Claims will be located in the payload structure of a JWT

### [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

* If I get a JWT and I can decode the payload, how can we call that secure?
Because the JWT will still need the correct promise method in order to be read
* If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
The calculated value of the hash payload and secret
* Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

  >   Let's assume Alice wants to send a JWT to Bob. They both know some shared secret. Mallory doesn't know that secret, but wants to interfere and change the JWT. To prevent that, Alice calculates Hash(payload + secret) and appends this as signature.
When receiving the message, Bob can also calculate `Hash(payload + secret)` to check whether the signature matches. If however, Mallory changes something in the content, she isn't able to calculate the matching signature (which would be `Hash(newContent + secret)`). She doesn't know the secret and has no way of finding it out. This means if she changes something, the signature won't match anymore, and Bob will simply not accept the JWT anymore.
Let's suppose, I send another person the message `{"id":1}` and sign it with `Hash(content + secret)`. (+ is just concatenation here). I use the `SHA256 Hash` function, and the signature I get is: `330e7b0775561c6e95797d4dd306a150046e239986f0a1373230fda0235bda8c`. Now it's your turn: play the role of Mallory and try to sign the message `{"id":2}`. You can't because you don't know which secret I used. If I suppose that the recipient knows the secret, he CAN calculate the signature of any message and check if it's correct.

### [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

* Why use JWT?
JWTs are a good way of securely transmitting information between parties because they can be signed, which means you can be sure that the senders are who they say they are.
* JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
The JWS Compact Serialization Overview describes how the JWT (JWS) gets base 64 encoded, but I actually don't see anything present about something like data compression. From what I can see, compact just seems to be referring to the fact that the JWT is fairly small.
As for self-contained, I believe this refers to the fact that a JWT acts as an independent passport of sorts. That is, in at least some cases, a server or consumer of a JWT only needs to check the claims of that JWT to make an authentication decision. In other words, the JWT itself contains all the information necessary to make use of it.

### [stack overflow JWT](https://stackoverflow.com/questions/57086586/jwts-compact-and-self-contained)

* What are the three components (the structure) of a JWT signature?
  * Header
  * Payload
  * Signature

Bookmark and Review
[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
