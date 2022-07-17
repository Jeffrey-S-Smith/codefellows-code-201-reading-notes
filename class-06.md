# Readings: Problem Domain, Objects, and the DOM

## JavaScript Object Basics

* How would you describe an object to a non-technical friend you grew up with?
  
  I would describe a object to my friend it is a standalone enitity, with properties and type. For example take a cup is an object, with properties. A cup has color, a design, weight, a material it is made of and etc.

* What are some advantages to creating object literals?

  To my mind object literals have two advantages. One they are used by many plugins such as jQuery so people are familier and they are easy to read. Making them easy to pass through data into a plugin. It's easy to create both public and private methods

* How do objects differ from arrays?

  Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value). 
  
  Arrays are a special type of variable that is also mutable and can also be used to store a list of values.

* Give an example for when you would need to use bracket notation to access an     object’s property instead of dot notation.

  Use brackets notation only when you have the name with like dashes or something similar invalid. And also if the name is stored in a variable.

* Evaluate the code below. What does the term this refer to and what is the advantage to using this?

```js script
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

In JavaScript, the this keyword refers to an object.

Which object depends on how this is being invoked (used or called).

The this keyword refers to different objects depending on how it is used

## Introduction To The DOM

* What is the DOM?

The DOM (Document Object Model) is an interface that represents how your HTML and XML documents are read by the browser. It allows a language (JavaScript) to manipulate, structure, and style your website.

* Briefly describe the relationship between the DOM and JavaScript.

JavaScript allows you to manipulate the DOM AKA Document object model that controls the client side scripting.

## Questions or Comments (If no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.)
I would like to know more about what this is used for and do you use it often?

## Things I want to know more about
More about this?

### Resources used

[JavaScript object basics. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics),
[Introduction to the DOM. mdn web docs_](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction),
[JavaScript Basics. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics),
[What’s the difference between primitive values and object references in JavaScript? by Chris Geelhoed](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b),
[Understanding The Problem Domain Is The Hardest Part Of Programming? by John Sonmez](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
