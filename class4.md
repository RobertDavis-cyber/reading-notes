# Class 4 Reading Notes Structure Web Pages with HTML

Here are my notes

# Wireframe and Design

A website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website.

1. InVision is the online whiteboard and productivity platform powering the future of work. See how InVision Freehand is purpose-built for team collaboration

https://www.invisionapp.com/

2. MiroMirofor Visual Collaboration
Scalable, secure, cross-device and enterprise-ready team collaboration whiteboard for distributed teams

https://miro.com/app/board/uXjVPRlT1ac=/

 # Mozilla HTML Basics

 # 1. HTML (HyperText Markup Language) is the code that is used to structure a web page and its content. 

The main parts of our element are as follows:

The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

The content: This is the content of the element, which in this case, is just text.

The element: The opening tag, the closing tag, and the content together comprise the element.

# Anatomy of an HTML document

# Example

<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image" />
  </body>
</html>

# Images. 

# 1. <img src="images/firefox-icon.png" alt="My test image" />

Embeds an image into our page in the position it appears. It does this via the src (source) attribute, which contains the path to our image file.

We have also included an alt (alternative) attribute. In the alt attribute, you specify descriptive text for users who cannot see the image, possibly because of the following reasons:

They are visually impaired. Users with significant visual impairments often use tools called screen readers to read out the alt text to them.
Something has gone wrong causing the image not to display. For example, try deliberately changing the path inside your src attribute to make it incorrect. If you save and reload the page, you should see something like this in place of the image:

# Semantics

# 1. Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?

# Semantic elements Examples

<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>

# Class 4 Code 201 Reading Notes

# My Reading Journal
**My reading journal for seattle-code-201d92**

# Readings: Readings: HTML Links, JS Functions, and Intro to CSS Layout Assignment 4
 
*Resources*
Learn HTML (https://developer.mozilla.org/en-US/docs/Learn/HTML)

Creating Hyperlinks (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

# Questions
 
-1. To create a basic link, we wrap text or other content inside what element?
 
 <p><a href="https://www.mozilla.org/firefox/">
  Download Firefox
</a></p>
 
-2. The href attribute contains what information?
 
 href attribute specifies the URL of the page the link goes to. For <base> elements, the href attribute specifies the base URL for all relative URLs on a page. For <link> elements, the href attribute specifies the location (URL) of the external resource (most often a style sheet file).
 
-3. What are some ways we can ensure links on our pages are accessible to all readers?

Mouse users will at least be able to click on the links in the drop-down menu, but keyboard users cannot access the drop-down menu, so the link is completely useless and all of the link destinations in the drop-down menu are completely inaccessible to them. One solution is to abandon the drop-down menu and instead use standard hypertext links. Another solution is to specify a real link destination (e.g. href="products.htm") which would list the same links that are available via the drop-down menu. For more information see example 2 in onMouseOver section of the JavaScript Event Handlers article.

*Resources*
Links and Hypertext (https://webaim.org/techniques/hypertext/)

# CSS Layout

#CSS Layout: Normal Flow CSS Layout: Positioning
 
-1. What is meant by “normal flow”?
 
-2. What are a few differences between block-level and inline elements?
 
-3. ___ positioning is the default for every html element.
 
-4. Name a few advantages to using absolute positioning on an element.
 
-5. What is a key difference between fixed positioning and absolute positioning?
 
 *Resources*
(https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
 
 *Resources*
(https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
 
*Resources*
(https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)
 
 
 
 
