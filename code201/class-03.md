## HTML Chapter 3: “Lists” 
HTML provides us with three different types to use list :
* Ordered lists are lists where each item in the list is numbered. `<ol>`
Each item in the list is placed between an opening `<li>` tag
and a closing `</li>` tag. (The li stands for list item.)

* Unordered lists are lists that begin with a bullet point.`<ul>`
Each item in the list is placed between an opening `<li>` tag
and a closing `</li>` tag. (The li stands for list item.)

* Definition lists are made up of a set of terms along with the definitions for each of those terms.`<dl>`
Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements.
`<dt>` This is used to contain the term being defined (the definition term).
`<dd>` This is used to contain the definition.
### summary
* There are three types of HTML lists: ordered, unordered, and definition.
* Ordered lists use numbers.
* Unordered lists use bullets.
* Definition lists are used to define terminology.
* Lists can be nested inside one another


## HTML Chapter 13: “Boxes” 
CSS treats each HTML element as if it lives in its own box.
By default a box is sized just big enough to hold its contents.
The most popular ways to specify the size of a box are to use pixels, percentages, or ems.
* ***pixels*** have been the most popular method because they allow designers to accurately control their size.
* ***percentages***, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.
* ***ems***  the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.

#### Every box has three available properties that can be adjusted to control its appearance:
* ***Border*** Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

* ***Margin***Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

* ***Padding*** Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

### Summary

* CSS treats each HTML element as if it has its own box.
* You can use CSS to control the dimensions of a box.
* You can also control the borders, margin and padding
  for each box with CSS.
* It is possible to hide elements using the display and visibility properties.
* Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
* Legibility can be improved by controlling the width of boxes containing text and the leading.
* CSS3 has introduced the ability to create image borders and rounded borders.


## Chapter 2: “Basic JavaScript Instructions” 
***ARRAYS*** An array is a special type of variable. It doesn't just store one value; it stores a list of values.
* You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).
* The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
there is 2 ways to create an array :-
1. `colors= ['white','black','custom'];`
2. `var colors = new Array('white ','black','custom ');`


## Chapter 4: “Decisions and Loops” 
In JavaScript we have the following conditional statements:

1. Use if to specify a block of code to be executed, if a specified condition is true
``` 
if (condition) {
  //  block of code to be executed if the condition is true
}
```
2. Use else to specify a block of code to be executed, if the same condition is false
```
if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}
```
3. Use else if to specify a new condition to test, if the first condition is false
```
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}
```
4. Use switch to specify many alternative blocks of code to be executed
```
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```
### Loop
Loops are handy, if you want to run the same code over and over again, each time with a different value.
In JavaScript we have the following loops statements:
1. for - loops through a block of code a number of times
```
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

2. for/in - loops through the properties of an object

3. for/of - loops through the values of an iterable object

4. while - loops through a block of code while a specified condition is true
```
while (condition) {
  // code block to be executed
}
```
5. do/while - also loops through a block of code while a specified condition is true



