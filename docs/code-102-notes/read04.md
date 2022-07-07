---
layout: default
title: Code 102 | Read 04
parent: Code 102 Notes
nav_order: 5
---

# Read 04: HTML review

HTML websites can be quickly designed using wireframe drawings. These drawings quickly sketch out what type and general placement of content that will be displayed on the website or app. This can be done easily with pen and paper but can also be done digitally at [wireframe.cc](https://wireframe.cc)

HTML serves as the frame for how a website will be delivered. There is some customization available but pure HTML websites will lack the more advanced capabilities provided by CSS or JavaScript. The basics for this markup language can be found at [HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

While implementing HTML you can use various commands to make content appear to take the parameters of “defined” HTML tags. An example of this is the following code, 

```html
<span> style="font-size: 32px; margin: 21px 0;">Is this a top level heading?</span>
```

Will display the below text

<span style="font-size: 32px; margin: 21px 0;">Is this a top level heading?</span>
 
This is the same "look" as an '<    h1>' tag but the top code will not have the inherent characteristics of a pure '<   h1>' tag as seen below

<h1>This is the largest heading</h1>


Elements will make up the main content of an HTML file. One resource that goes in depth for what each element tag can do is located [here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

## What the heck are semantic elements??

From FreeCode Camp

> Elements such as <    header>, <  footer> and <   article> are all considered semantic because they accurately describe the purpose of the element and the type of content that is inside them.

In other words semantic elements make reading HTML easier if you are not too familiar with HTML. One example of that is shown below from [this site](https://www.freecodecamp.org/news/semantic-html5-elements/#:~:text=Semantic%20HTML%20elements%20are%20those,content%20that%20is%20inside%20them)

**Semantic elements used** 

### <   header></   header>  
  

**Non-semantic elements used**

### <   div id="header"></  div>  
