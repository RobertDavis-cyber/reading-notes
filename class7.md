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

