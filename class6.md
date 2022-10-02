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
