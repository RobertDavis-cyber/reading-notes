## Class 10 Reading Notes My Reading Journal for seattle-code-301d92

## Readings: In memory storage

## Understanding the JavaScript Call Stack

1.What is a ‘call’?--*Javascript Function call() The JavaScript Function call() method calls a function with a given this value and arguments provided individually*

2.How many ‘calls’ can happen at once?--*Infinitely. Not really until you don't overflow the stack with function calls. Since each time a function is called all the variables used need space to be store in stack and stack is of limited size so someway in middle of any hundredth or thousandth call you will run out stack for function call.*

3.What does LIFO mean?--*It means last in, first out. It is a method for handling data structures where the first element is processed last and the last element is processed first.*

4.Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
(https://commons.wikimedia.org/wiki/File:Call_stack_layout.svg#/media/File:Call_stack_layout.svg)

![Screenshot 2022-12-08 at 8 25 44 PM](https://user-images.githubusercontent.com/114452551/206638633-34f24dd1-f696-4c52-820a-ced44748d357.png)

5.What causes a Stack Overflow?--*A stack overflow is a type of buffer overflow error that occurs when a computer program tries to use more memory space in the call stack than has been allocated to that stack.*

## JavaScript error messages

1.What is a ‘reference error’?--*The ReferenceError object represents an error when a variable that doesn't exist (or hasn't yet been initialized) in the current scope is referenced.*

2.What is a ‘syntax error’?--*An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code.*

3.What is a ‘range error’?--*A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value.*
*

4.What is a ‘type error'?--*The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.*

5.What is a breakpoint?--* breakpoint is a point in the program where the code will stop executing.*

6.What does the word ‘debugger’ do in your code?--*Debugging means to run your code step by step in a debugging tool like Visual Studio, to find the exact point where you made a programming mistake. *

## Bookmark and Reaview

JavaScript errors reference on MDN

(https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
(https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
