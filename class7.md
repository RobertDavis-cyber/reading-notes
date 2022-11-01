# My Reading Journal
My reading journal for Code Fellos 102n65

Reading 7

# MDN Control Flow

* Control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}
Copy to Clipboard

*Resources*
MDN Control Flow (https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

JavaScript Reference - Control flow on MDN (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference#control_flow)
Statements (Control flow) on MDN (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)

# Reading and Demo References

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Example
// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}
*Resources*
(https://www.w3schools.com/js/js_functions.asp)

JavaScript Operators

Example
Assign values to variables and add them together:

let x = 5;         // assign the value 5 to x
let y = 2;         // assign the value 2 to y
let z = x + y;     // assign the value 7 to z (5 + 2)

*Resources*
(https://www.w3schools.com/js/js_operators.asp)

# Class 7 Code 201 Reading Notes

# My Reading Journal
**My reading journal for seattle-code-201d92**

# Readings: Readings: Object-Oriented Programming, HTML Tables

# Domain Modeling

-1. Explain why we need domain modeling.

In software engineering, a domain model is a conceptual model of the domain that incorporates both behavior and data. In ontology engineering, a domain model is a formal representation of a knowledge domain with concepts, roles, datatypes, individuals, and rules, typically grounded in a description logic

(https://en.wikipedia.org/wiki/Domain_model)

*Resources* 
(https://github.com/codefellows/domain_modeling#domain-modeling)

# HTML Table Basics

-1. Why should tables not be used for page layouts?

The World Wide Web Consortium (W3C®) discourages use of tables for layout because they are striving for a web in which content and structure are completely separate from presentation.

-2. List and describe 3 different semantic HTML elements used in an HTML <table>.
 
-1.HTML <section> Element
The <section> element defines a section in a document.

According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."

Examples of where a <section> element can be used:

Chapters
Introduction
News items
Contact information
A web page could normally be split into sections for introduction, content, and contact information.
  
-2. HTML <article> Element
The <article> element specifies independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

Examples of where the <article> element can be used:

Forum posts
Blog posts
User comments
Product cards
Newspaper articles
  
-3. HTML <header> Element
The <header> element represents a container for introductory content or a set of navigational links.

A <header> element typically contains:

one or more heading elements (<h1> - <h6>)
logo or icon
authorship information
Note: You can have several <header> elements in one HTML document. However, <header> cannot be placed within a <footer>, <address> or another <header> element.
  
 *Source* (https://www.w3schools.com/html/html5_semantic_elements.asp#:~:text=Examples%20of%20semantic%20elements%3A%20%3Cform,%3E%20%2D%20Clearly%20defines%20its%20content.)
  
*Resources* 
(https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
  
# Introducing Constructors
  
-1. What is a constructor and what are some advantages to using it?
  
 A constructor in Java is a special method that is used to initialize objects. The constructor is called when an object of a class is created. It can be used to set initial values for object attributes
  
-2. How does the term this differ when used in an object literal versus when used in a constructor?
  
Objects created using object literal are singletons, this means when a change is made to the object, it affects the object entire the script. Whereas if an object is created using constructor function and a change is made to it, that change won't affect the object throughout the script.
  
*Resources* 
(https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
 
  
 # Object Prototypes Using A Constructor NOTE: This is a very common front end developer interview question

  
 -1. Explain prototypes and inheritance via an analogy from your previous work experience.
  
In JavaScript, an object can inherit properties of another object. The object from where the properties are inherited is called the prototype. In short, objects can inherit properties from other objects — the prototypes.
  
This question I am confused on?  Ask instructor via analogy from your previous work experience?

  
 *Resources*
 (https://ui.dev/beginners-guide-to-javascript-prototype)
  
 # Bookmark and Read Over Reference 
  
  *Resources*
  
  HTML Table Advanced Features and Accessibility. (https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
  
  # Things I want to know more about!
  
  I would like to get more information about Object Prototypes Using A Constructor NOTE: This is a very common front end developer interview questions.
  

