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

