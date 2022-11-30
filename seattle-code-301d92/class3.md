# Class 2 Reading Notes

# My reading journal for seattle-code-301d92

# Readings: Passing Functions as Props

# React Docs - lists and keys

1. What does .map() return?---*Map Method in ReactJS: Usage. Conclusion. Map is a type of data structure or data collection that is used to store the data in the form of key and value pairs.*

2. If I want to loop through an array and display each value in JSX, how do I do that in React?---*Use the map() method to iterate over the array. The function you pass to map() gets called for each element in the array. The method returns a new array with the results of the passed in function.*

3. Each list item needs a unique ____.---*Key?  Keys nned to be assigned to element in a loop to give idenity to elements in React.*

4. What is the purpose of a key?---*Keys nned to be assigned to element in a loop to give idenity to elements in React.*

# The Spread Operator

1. What is the spread operator?---*Allows us to quickly copy all or part of an existing array or object into another array or object.*

2. List 4 things that the spread operator can do.---*Make shallow copies of objects,Merge multiple objects together,Combine arrays and Pass multiple arguments into a function.*

3. Give an example of using the spread operator to combine two arrays.---*You can use either the spread operator [...array1, ...array2] , or a functional way [].concat(array1, array2) to merge 2 or more arrays.*

4. Give an example of using the spread operator to add a new item to an array.---*spread operator after the new values. For example: let a = [1, 2, 3, 4, 5]; let b = [0, ...a]; console. log(a); console*

5. Give an example of using the spread operator to combine two objects into one---*To merge objects into a new one that has all properties of the merged objects, you have two options:

Use a spread operator ( ...)
Use the Object.assign() method*

# Video How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?---*Couldn't see the video?*

2. In your own words, what does the increment function do?---*The setCount() method archives two tasks assign incremented value to the “count” React state and render updated value on screen.*

3. How can you pass a method from a parent component into a child component?---*call an alert method in the childToParent function and pass that function as a prop to the child component. And in the child component, accept the childToParent function as a prop. Then assign it to an onClick event on a button. *

4. How does the child component invoke a method that was passed to it from a parent component?---*To call a child's function from a parent component in React.

Wrap the Child component in a forwardRef .
Use the useImperativeHandle hook in the child to add a function to the Child .
Call the Child's function from the Parent using the ref, e.g. childRef. current. childFunction() .*

# Bookmark 

React Tutorial through ‘Declaring a Winner’
(https://reactjs.org/tutorial/tutorial.html)

React Docs - Lifting State Up
(https://reactjs.org/docs/lifting-state-up.html)

## Things I want to know more about.....

*I would like to know more about real work cases as a consumer that React is used and see an example from an app or website the code to understand it.*



