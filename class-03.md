# HTML Lists, Control Flow with JS, and the CSS Box Model

## Ordered and Unordered lists

1. When should you use an unordered list in your HTML document?

* The \<ul> element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.

* The \<ul> and \<ol> elements may be nested as deeply as desired. Moreover, the nested lists may alternate between \<ol> and \<ul> without restriction.

* The \<ol> and \<ul> elements both represent a list of items. They differ in that, with the \<ol> element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the \<ol> element should be used, otherwise you can use \<ul>.

2. How do you change the bullet style of unordered list items?

CSS - list-style-type

3. When should you use an ordered list vs an unorder list in your HTML document?

You should use a ordered list in your HTML document when you have items ordered by number

4. Describe two ways you can change the numbers on list items provided by an ordered list?

To make the ordered list show letters instead of numbers, specify type="A" for uppercase and type="a" for lowercase letters in the \<ol> element.

CSS - list-style-type: decimal;
    list-style-position: inside;

## Learn CSS

### The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Margin is outer space of an element, while padding is inner space
  of an element. Margin is the space outside the border of an
  element, while padding is the space inside the border of it.
  Margin accepts the value of auto: margin: auto , but you can't
  set padding to auto.

2. List and describe the four parts of an HTML elements box as referred to by the box model

* Content - The content of the box, where text and images appear.

* Padding - Clears an area around the content. The padding is transparent.

* Border - A border that goes around the padding and content.

* Margin - Clears an area outside the border. The margin is transparent.

## Learn JS

### Arrays, Operators and Expressions, Conditionals, Loops

1. What data types can you store inside of an Array

The values in an array can be any type, so that arrays may contain values that are simple reals or integers, vectors, matrices, or other arrays. Arrays are the only way to store sequences of integers, and some functions in Stan, such as discrete distributions, require integer arguments.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why

```js
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```
people array is valid JavaScript array. Through a function calling the variable people.

3. List five shorthand operators for assignment in javascript and describe what they do.

--  += Addition assignment
--  -= Subtraction assignment
--  *= Multiplication assignment
--  /= Division assignment
--  %=  Remainder assignment

4. Read the code below and evaluate the last expression and explain what the result would be and why.

```js
let a = 10;
 let b = 'dog';
 let c = false;
 // evaluate this
 (a + c) + b;
```
The expression result will be false.

 5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

 In JavaScript we have the following conditional statements: Use if to specify a block of code to be executed, if a specified condition is true. Use else to specify a block of code to be executed, if the same condition is false. Use else if to specify a new condition to test, if the first condition is false.

 Suppose we want to go out for a movie the first thing we will check before moving out is if it is raining or not(if condition) if it is raining we will not go to watch the movie(blocks inside if condition didn't run because it is raining outside and the condition is not met).

 6. Give an example of when a Loop is useful in JavaScript.

 In programming, loops are used to repeat a block of code. For example, if you want to show a message 100 times, then you can use a loop.

### If there are no questions provided, summarize and explain this topic via an analogy from your previous work or home experience

4. Read the code below and evaluate the last expression and explain what the result would be and why. In section I did not understand.

### Things I want to know more about
