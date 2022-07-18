# Readings: Object-Oriented Programming, HTML Tables

## Domain Modeling

1. Explain why we need domain modeling.

Domain modeling is a great tool for Agile enterprise to carry out a common language and a fundamental structure important for the analysis of features and epics. The domain model is defined and continuously refactored as enterprise knowledge about the domain improves and the system functionality evolves.

## HTML Table Basics

1. Why should tables not be used for page layouts?

Tables shouldn't be used for page layouts because they are: Slow to render as the browser needs to download most - if not all - of the table to render it properly. They require more HTML than non-table layouts which means slower loading and rendering, as well as an increased bandwidth usage

2. List and describe 3 different semantic HTML elements used in an HTML \<table>.

\<footer> Defines a footer for a document or section

\<header> Specifies a header for a document or section

\<main> Defines marked/highlighted text

\<nav> element defines a set of navigation links.

\<aside> element defines some content aside from the content it is placed in (like a sidebar).

\<time> Defines a date/time

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

One of the benefits of using a constructor over a method is that you can be assured the constructor was called and the work within the constructor was performed. The language specifies that to construct an object a constructor must be called.

2. How does the term this differ when used in an object literal versus when used in a constructor?

The main difference here is what you can do with it. With the constructor function notation you create an object that can be instantiated into multiple instances (with the new keyword), while the literal notation delivers a single object, like a singleton.

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

Simply put, prototypical inheritance refers to the ability to access object properties from another object. We use a JavaScript prototype to add new properties and methods to an existing object constructor. We can then essentially tell our JS code to inherit properties from a prototype.

* NOTE: This is a very common front end developer interview question

## Questions or Comments (If no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.)
Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.
## Things I want to know more about

### Resources used

[Domain Modeling githubpage. by Ryan Sobol, Sam Hamm, Keli Hansen](https://github.com/codefellows/domain_modeling#domain-modeling),
[HTML Table Basics. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics),
[Introducing Constructors. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors),
[Object Prototypes Using A Constructor. by Tyler McGinnis](https://ui.dev/beginners-guide-to-javascript-prototypes),
[HTML Table Advanced Features and Accessibility. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
