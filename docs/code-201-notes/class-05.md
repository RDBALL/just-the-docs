---
layout: default
title: Code 201 | Class 05
parent: Code 201 Notes
---

## Using Images In HTML

## Read Common Image Types and Choosing Image Formats

### What is a real world use case for the alt attribute being used in a website?

Alt text is useful for any instances when an image can not be displayed for any variety of reasons. The alt text would serve as a written description for what the image would display.

### How can you improve accessibility of images in an HTML document?

**Choosing appropriate text alternatives:**

* Imagine that you’re reading the web page aloud over the phone to someone who needs to understand the page. This should help you decide what (if any) information or function the images have. If they appear to have no informative value and aren’t links or buttons, it’s probably safe to treat them as decorative.

**Prioritize information in text alternative:**

* Aim to put the most important information at the beginning.

**Length of the text alternative:**

* The alt text should be the most concise description possible of the image’s purpose. If anything more than a short phrase or sentence is needed, it would be better to use one of the long description methods discussed in complex images.

**Responsive design:**

* Icons with text labels will often drop the text labels when viewed on smaller screens. Ensure that icons are readable at that size, understandable without text, and have text descriptions.

**Punctuation within alt attributes:**

* As for any text, using punctuation in the text alternative makes the information easier to understand. In particular, remember to add space characters in the alt text when there’s no space character between the image and adjacent text, to avoid having words running together when they are read by a screen reader.

* If you use a null (empty) text alternative (alt="") to hide decorative images, make sure that there is no space character in between the quotes. If a space character is present, the image may not be effectively hidden from assistive technologies. For instance, some screen readers will still announce the presence of an image if a space character is put between the quotes.

**Superfluous information in the text alternative:**

* Usually, there’s no need to include words like “image”, “icon”, or “picture” in the alt text. People who can see will know this already, and screen readers announce the presence of an image. In some situations, it may be important to distinguish between paintings, photographs, or illustrations, etc., but it’s best to avoid the more generic use of the terms.

**SVG graphics:**

* SVG graphics can be referenced in the src attribute of an `<img>` element like other image formats (PNG, JPEG, GIF). In this case, the examples of this tutorial can be used with SVG as well.

* As SVG images consist of tags like HTML, their code can also be used in HTML5 directly. In this case you can provide a text alternative in a `<title>` element within the SVG image. To improve accessibility support, that title should be referenced from an aria-labelledby attribute of the `<svg>` element, for example:

* `<svg aria-labelledby="svgtitle1"> <title id="svgtitle1">Settings</title> [other svg code] </svg>`

**Logos:**

* Logo images with text are exempt from some of the accessibility requirements. For instance, there is no minimum contrast requirement.

[w3 HTML IMG tips](https://www.w3.org/WAI/tutorials/images/tips/)

### Provide an example of when the figure element would be useful in an HTML document

You would use a `<figure>` if you are going to include an image, illustration or any other type of visual media that is referenced within the HTML document. These elements can be repositioned without interrupting the normal flow of the webpage.

### Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community

* GIFs are used for animations just like the old motion picture film. They only contain visual data and can not utilize sound.
* SVGs are infinitely scalable images (built with math) that can show static visual media at any size.

### What image type would you use to display a screenshot on your website and why?

I would use a PNG due to maintaining more data fidelity than a JPG.

## Using Color in CSS. Styling HTML Text Elements

### Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge

If you imagine the webpage as s multilayered plane the background color elements will be displayed behind foreground elements

### Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

* I would ask my friend what type of color palette he would like to work with and if he has any website designs that he likes the styling of. I would take their comments and create an initial color palette for their approval.

* Once approved I would then begin to group like items within the HTML document and add color in accordance to the approved palette. I would make periodic check ins with my friend to make sure that whatever I was styling remained to their liking.

### What should you consider when choosing fonts for an HTML document?

* Beyond all else you should focus on readability and scalability
* Identify if the chosen font can be easily read on all required screen sizes
* Don’t choose a highly stylized font for the main content of your page if it either does not fit with the overall design of the webpage or can’ be easily read

### What do font-size, font-weight, and font-style do to HTML text elements?

* `font-size:` will adjust the size of your font. It can be measured in multiple different ways
* `font-weight:` will adjust the stroke width of each typed character. This will cause characters to look thicker or ‘bold’
* `font-style:` will add simple styling designs to your text such as underlined or strikethrough.

### Describe two ways you could add spacing around the characters displayed in an h1 element

* You can use the `letter-spacing:` property along with a type of measurement to add whitespace between typed characters
* You can use the `line-height:` property to add additional whitespace above and below the identified element characters
