# HTML Lists, Control Flow with JS, and the CSS Box Model


## Lists


We use lists in HTML when we need to group a set of related items in HTML to structure our website, for example when we need to navigate into different pages inside of it we use an unordered list. 
There are three types of lists in HTML:

+ **Unordered lists**They are lists in which each item begins with bullets.
It is created with Ul and then li with the content inside each of the li's closing tags.

+ **Ordered lists** are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number .
+ **Definition  lists** lists used to define a term. It is created using dl then dt with the defined term and dd with the difintion of the term.

# Boxes
All HTML elements can be considered as boxes.
In CSS, the term "box form" is used when talking about design and layout.

A CSS box template is basically a box that wraps around each HTML element. It consists of: margins, borders, padding, and actual content.
**width & height:** used to determine the dimensions of the box by increasing/decreasing the width and height.


**scroll:** used to show not showing information and that happens when there is too much information. 
**Margin:** It is the space between the element and another element.
**Border:** boxes have borders and it is used to separate edges of one box from another.
**padding:** it is the space between the content in the box and the border of the element.
**Text aligning:** used to determine where to align the text.
**hidden:** hides extra content.
**inline/block:** using the display to change from inline to block or vice versa.

## Arrays
Array is an object that stores a fixed size of values , and it collection of variables of the same typ

### operators:
* String operator
* Comparsion operator
* Arithmetic operator
## Decisions and Loops
Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return **true** or **false** when analysed. A loop will continue running until the defined condition returns **false**. 
_Loops can execute a block of code a number of times._

The three most common types of loops are:
- for
- while
- do while

This loop will keep running until the condition becomes false and will continue to run for as long as the condition in the parentheses is true, so it can be used in unlimited time.
### for loop:-
for loops typically used in looping through items or a limited number of times, unlike while loop who can loop unlimited times.
### Do while loop:-
The difference between this loop and the while loop is that this loop will check the condition after running the code. therefore, the code could be repeated unlimited times.
do {
   *Statement(s);*
   } 
while (*condition*);
### while loop:-
This loop will keep running until the condition becomes false and will continue to run for as long as the condition in the parentheses is true, so it can be used in unlimited time.
