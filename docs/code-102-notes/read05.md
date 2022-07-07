---
layout: default
title: Code 102 | Read 05
parent: Code 102 Notes
nav_order: 6
---

# Read: 05 - Design web pages with CSS

Terms:
> Cascading Style Sheets (CSS)

CSS allows you to add style to the structure (HTML) of a webpage. The styles.css file can be placed within the same directory of your index.html file and can be linked (activated) through a link 

```markdown
<link rel="stylesheet" href="styles.css">
```


The above code would be placed within the <head> of the HTML document that you would like to stylize. 

Let’s break down the above code and see what it does.

- The initial <link> tag identifies that we are wanting to link something to this HTML page

- rel=”stylesheet” identifies that the relationship between the linked item and the current HTML page

- href=”styles.css” identifies that the stylesheet we want to link to the HTML document is the file “styles.css” located within the same directory as our HTML document

From there we can add “class=”specified-name” within tags in index.html to identify specific elements that we would like to modify using the styles.css file

Styles follow the below syntax

> Element you want to style **{**    
	*Way that you want to style it*   
**}** 

An example for modifying text that has a class of "navigation"

```css
.navigation {  
  font-family: 'Goldman', cursive;  
  font-size: 30px; 
  font-weight: bold; 
  color: white; 
  display: flex; 
  justify-content: space-evenly;  
  align-items: center;  
  padding: 30px 10%;  
}
```
What can you style with CSS?

From W3 schools:
> With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

Resources to help find CSS variables that can help style your HTML page  
- [W3Schools](https://www.w3schools.com/html/html_css.asp)  
- [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/CSS)  
- [CSS Tricks](https://css-tricks.com/guides/)