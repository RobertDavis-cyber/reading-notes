# Class 4 Reading Notes

# My reading journal for seattle-code-301d92

# Readings: Readings: React and Forms

# React Docs - Forms

1. What is a ‘Controlled Component’?--*Controlled Component in React are those in which form's data is handled by the component's state. It takes its current value through props and makes changes through callbacks like onClick.*

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.--*This I am not sure on, I read the docs and searched but don't understand it.*

3. How do we target what the user is entering if we have an event handler on an input field?--*Declare a state variable that tracks the value of the input field, Add an onChange prop to the input field, and Use event. target. value to get the input field's value and update the state variable.*

# The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?--*The  ternary operator, you can display the contents on the basis of one condition where everything depends on the condition true and false we can put the contents on the conditional basis.*

2. Rewrite the following statement using a ternary statement:--**

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

function testNum(a) {
  let result;
  if (a > 0) {
    result = 'positive';
  } else {
    result = 'NOT positive';
  }
  return result;
}

console.log(testNum(-5));
// expected output: "NOT positive"

Not sure how to do this but I saw this example reference (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)


# Bookmarks

React Bootstrap - Forms
(https://react-bootstrap.github.io/forms/overview/)
React Docs - conditional rendering
(https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about....

*Question #2 not sure on this and would a simple explanation or visual example to understand.*
