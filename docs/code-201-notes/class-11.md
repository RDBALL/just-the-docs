---
layout: default
title: Code 201 | Class 11
parent: Code 201 Notes
---

## Video and Audio Content

### Explain how the ability to use video and audio on the web has evolved since the early 2000s

* Since the early 2000s, embedded videos and audio on web pages has become commonplace. During the early 2000s there was often not enough bandwidth to support streaming videos and even if there was, HTML did not support embedded videos or audio yet. To be able to stream media you would need to rely on a plugin such as Flash or Silverlight to handle the encoding and rendering of media.

### Describe the use of the `src` and `controls` attributes in the `<video>` element

* `src` works the same way with a `<video>` element as it does with a `<img>` element. It contains the URL of the video that will be embedded within this element.
* `controls` provides the user with basic controls for the video. This would include start, stop, and volume control.

### Why is it important to have fallback content inside the `<video>` element?

* Fallback content allows you to include an `alt` sequence to provide a direct link to the video if the users device is unable to play the embedded content.

## A Complete Guide To Grid

### How does Grid layout differ from Flex?

* Grid constraints elements to predetermined grids while flex will allow elements to grow or 'flex' in order to fit its content.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences

* Grid Container: consist of grid items contained within columns and rows
* Grid item: elements that are identified within the grid container
* Grid line: dividing lines that make up the structure of a grid container. They can either be horizontal or vertical

## Responsive Images

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

* Responsive images will ensure that the desired page layout is rendered across multiple devices or screen sizes.

### Define the following `<img>` attributes srcset and sizes. Write an example of how they are used

* `<img>`: used to embed an image onto a web page
* `srcset`: defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.
defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true.

### How is srcset more helpful for responsive images than CSS or JavaScript?

* `srcset` allows the browser to determine the best way to display the image attached to the srcset attribute.
