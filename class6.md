# My Reading Journal
My reading journal for Code Fellos 102n65

Reading 6

# Dynamic web pages with JavaScript  

What is Dynamic web pages with JavaScript:
- JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) style

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

# Introduction to JavaScript - basic output

JavaScript was used inside web browsers such as Mozilla Firefox, Internet Explorer, Chrome, Opera, or Safari. The author would include some JavaScript code in the HTML page the user receives when she visits a web site. That JavaScript code would run in the browser (what we call "client side", as opposed to running on the web server which is called "server side").

For example, we can distinguish 3 major parts of what we usually refer to as "JavaScript".

The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.
The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.
The server API (or just API) provided by Node.js or one of the other server-sid

*Resources*
Introduction to JavaScript - basic output (https://code-maven.com/introduction-to-javascript)

*examples/js/alert.html*

<script language="javascript">

alert("Hello World");

</script>

# JavaScript input with prompt and confirm

**prompt**

The fist one is called prompt. It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function. Then, in this example we use the document.write method to update the html with the text.

examples/js/prompt.html

<script>

var name = prompt("Your name:", "");
document.write("Hello ", name);

</script>

The textbox will be pre-filled with the content of the second parameter. This can be very useful if we would like to ask the user to edit some value. We can pre-fill the box with the old value.

examples/js/edit.html

<script>

var name = prompt("Please correct your e-mail address:", "foo@bar.co");
document.write("Your e-mail address is ", name);

</script>

confirm
The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.

Of course in order for this to make more sense you'll have to understand what true and false really mean and what this if - else construct does. If you have programming background then you probably already understand the code, and even if you don't have programming background you might figure out.

That code can basically be translated to the following English sentence:

If confirm returned true, print "Hello World", otherwise print "OK, I won't print it."

Or even better:

If the user presses OK when we asked "Shall I print Hello World?", then print "Hello World", otherwise print "OK, I won't print it."

examples/js/confirm.html

<script>

if (confirm("Shall I print Hello World?")) {
    document.write("Hello World");
} else {
    document.write("OK, I won't print it.");
}

</script>

*Resources*
CSS syntaxx (https://code-maven.com/javascript-input-with-prompt-and-confirm)


# Class 6 Code 201 Reading Notes

# My Reading Journal
**My reading journal for seattle-code-201d92**

# Readings: Readings: Problem Domain, Objects, and the DOM

# JavaScript Object Basics

-1. How would you describe an object to a non-technical friend you grew up with?

In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc.

-2. What are some advantages to creating object literals?

The advantages of using object literals to create objects include convenience, flexibility in declaration, and less code during declaration. You can drop an object literal anywhere in your program with no previous setup and it'll work.

-3. How do objects differ from arrays?

Objects represent “things” with characteristics (properties), while arrays create and store lists of data in a single variable.

-4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

Dot notation is faster to write and easier to read than bracket notation. However, you can use variables with bracket notation, but not with dot notation. This is especially useful for situations when you want to access a property but don't know the name of the property ahead of time.

-5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

-5. The this keyword refers to the current object the code is being written inside — so in this case this is equivalent to person.  Using this enables you to use the same method definition for every object you create.

Refer to age the the this

*Resources* 
JavaScript Object Basics (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

# Introduction To The DOM

-1. What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

-2. Briefly describe the relationship between the DOM and JavaScript.

The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.

*Resources* 
Introduction To The DOM (https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

# Bookmark and Review

Understanding the problem domain is the hardest part of programming.

What’s the difference between primitive values and object references in JavaScript?
(https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
