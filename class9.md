# My Reading Journal
My reading journal for seattle-code-201d92

Reading 9

# Why this topic matters studying in this module.

*It is useful Web forms are a important tool for interacting with users — for collecting data from users, or allowing them to control a user interface.

# HTML Forms

-1. Why are forms so important in web development?

*HTML Forms are required, when you want to collect some data from the site visitor.*

-2. When designing a form, what are some key things to keep in mind when it comes to user experience?

*The first thing anyone will see on your form is the title. It should be clear, specific, and let the user know exactly where they are. Field Labeling: In general, field labels should be placed above or below your fields, and not to the left or the right.*

-3. List 5 form elements and explain their importance.

*The HTML <form> element can contain one or more of the following form elements*


  -1. <input>
  One of the most used form element is the <input> element.  The <input> element can be displayed in several ways, depending on the type attribute.

  -2. <label>
  The <label> element defines a label for several form elements.  The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

  -3. <select>
  The <select> element defines a drop-down list:

  -4. <textarea>
  The <textarea> element defines a multi-line input field (a text area):

  -5. <button>
  The <button> element defines a clickable button:

*Resources*
(https://www.w3schools.com/html/html_form_elements.asp)
(https://web.dev/learn/css/flexbox/)](https://developer.mozilla.org/en-US/docs/Learn/Forms)
(https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
(https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

# Learn JS

-1. How would you describe events to a non-technical friend?

JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

-2. When using the addEventListener() method, what 2 arguments will you need to provide?
  
The addEventListener() is an inbuilt function in JavaScript which takes the event to listen for, and a second argument to be called whenever the described event gets fired. Any number of event handlers can be added to a single element without overwriting existing event handlers.
 
  Example *Resources*
  (https://www.geeksforgeeks.org/javascript-addeventlistener-with-examples/#:~:text=The%20addEventListener()%20is%20an,without%20overwriting%20existing%20event%20handlers.)
  
  <!DOCTYPE html>
<html>

<body>
	<button id="try">Click here</button>
	<h1 id="text"></h1>
	<script>
	document.getElementById("try").addEventListener("click", function(){
	document.getElementById("text").innerText = "GeeksforGeeks";
});
	</script>
</body>

</html>


-3. Describe the event object. Why is the target within the event object useful?
  
Image result for Describe the event object.  An event, like a button click, is represented as an object. When the user generates an event, the system creates an event object which is then sent to the listener that has been registered for the GUI component. Then, a method in the listener object is invoked.

-4. What is the difference between event bubbling and event capturing?
  
With bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements. With capturing, the event is first captured by the outermost element and propagated to the inner elements.
  
*Resources*
(https://stackoverflow.com/questions/4616694/what-is-event-bubbling-and-capturing#:~:text=With%20bubbling%2C%20the%20event%20is,propagated%20to%20the%20inner%20elements.) 

*Resources*

(https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
(https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)


# Bookmark and Review

*Resources*

(https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
(https://developer.mozilla.org/en-US/docs/Web/Events)
