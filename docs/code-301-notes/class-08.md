---
layout: default
title: Code 301 | Class 08
parent: Code 301 Notes
---

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

### What does REST stand for?

* Representational State Transfer

### REST APIs are designed around  ____?

* Resources

### What is an identifier of a resource? Give an example

* This is a URL that uniquely identifies the target resource).

* An example given from the reading would be a customer order

### What are the most common HTTP verbs?

* GET
* POST
* PUT
* PATCH
* DELETE

### What should the URIs be based on?

* URIs should be based on nouns

### Give an example of a good URI

```ts
      userinfo       host      port
          ┌──┴───┐ ┌──────┴──────┐ ┌┴┐
  https://john.doe@www.example.com:123/forum/questions/?tag=networking&order=newest#top
  └─┬─┘   └───────────┬──────────────┘└───────┬───────┘ └───────────┬─────────────┘ └┬┘
  scheme          authority                  path                 query           fragment
```

 ***[wikipedia URI](https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Syntax)***

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

* These are web APIs that expose a large number of small resources and should be avoided.

### What status code does a successful GET request return?

* 200

### What status code does an unsuccessful GET request return?

* 400

### What status code does a successful POST request return?

* 201 (created) or 200 (ok)

### What status code does a successful DELETE request return?

* 204

Bookmark and Review

[RegExr](https://regexr.com/)

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regex 101](https://regex101.com/)
