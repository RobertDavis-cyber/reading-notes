# Class 3 Reading Notes Git

**Here are my notes

**Version Control
-A system that allows you to revisit various versions of a file or set of files by recording changes.

**Local Version Control
-Local VCS entails one database on your hard disk that stores changes to files.

**Centralized Version Control
-This system entails a single server storing all changes and file versions, which can be accessed by various clients.

Distributed Version Control
-A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure.

# So, what is Git?

Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

States

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the database

Reference more about Git [GitHub Pages]([https://pages.github.com/](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/).

# Class 3 Code 201 Reading Notes

# My Reading Journal
**My reading journal for seattle-code-201d92**

# Readings: Learn HTML Assignment 3

# Ordered and Unordered Lists

-1. When should you use an unordered list in your HTML document?
-2. How do you change the bullet style of unordered list items?
-3. When should you use an ordered list vs an unorder list in your HTML document?
-4. Describe two ways you can change the numbers on list items provided by an ordered list?

*Resources*
LearnHTML (https://developer.mozilla.org/en-US/docs/Web/HTML)
Ordered (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
Unordered (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)


# Learn CSS

-1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
*CSS can be added to HTML documents in 3 ways: Inline - by using the style attribute inside HTML elements. Internal - by using a <style> element in the <head> section. External - by using a <link> element to link to an external CSS file.
   
-2. List and describe the four parts of an HTML elements box as referred to by the box model.
*Not sure will read more and ask in class


*Resources*
(https://developer.mozilla.org/en-US/docs/Learn/CSS)
(https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
  
# Learn JS
  
-1. What data types can you store inside of an Array?
-2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
-3. List five shorthand operators for assignment in javascript and describe what they do.
-4. Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
-5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
-6. Give an example of when a Loop is useful in JavaScript.

*Resources*
(https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

- What data type is a sequence of text enclosed in single quote marks?
Single (' ') and double (" ") quotes are used to represent a string in Javascript. Choosing a quoting style is up to you and there is no special semantics for one style over the other. Nevertheless, it is important to note that there is no type for a single character in javascript, everything is always a string
   
  *Resource*
  (https://www.w3schools.com/js/js_operators.asp](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
  (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
  (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
  (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
  (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
   
