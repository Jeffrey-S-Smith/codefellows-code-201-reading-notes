# Readings Overview

## Getting Started

1. Compose a short poem describing how HTTP sends data between computers.&nbsp;  
    HTTP is Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers so they can speak to each other. This is like the language we use to order our goods.

    When you type a web address into your browser (for an analogy like walking to the shop).

    The browser looks into the DNS server, and finds the real address of the server that the website lives on (finds the address of the shop).
    Then the browser sends an HTTP request a message to the server, asking it to send a copy of the website to the client (like you going to the shop and order your goods).   This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
    If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
    The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
    When browsers send requests to servers for HTML files, those HTML files often contain \<link> elements.
    Referencing external CSS stylesheets \<link> elements and JavaScript \<script> elements.
    It's important to know the order in which those files are parsed by the browser as the browser loads the page:

    First the  browser parses the HTML file first, and that leads to the browser recognizing any \<link>-element references to external CSS stylesheets and any \<script>-element references to scripts.
    when the browser parses the HTML, it sends requests back to the server for any CSS files it has found from \<link> elements, and any JavaScript files it has found from \<script> elements, and from those, then parses the CSS and JavaScript.

    Browser generates an in-memory DOM from the parsed HTML, generates an in-memory structure from the parsed CSS, and compiles and executes the parsed JavaScript.

    when the browser builds the DOM and applies the styles from the CSS and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

3. How can you find images to add to a Website?
    You can brows Google images and type in what type of image you are looking for. You can find a lot of sites like Unsplash that has images to that you can use. When looking for images you have to be careful of copyright laws.

4. How do you create a String vs a Number in JavaScript?

    In Javascript you create a string by (var, const, let) myVariable = 'Hello';&nbsp;  
    In Javascript you create a number by (var, const, let) myVariable = 6;

5. What is a Variable and why are they important in JavaScript?

    Variables are containers that store values. You start by declaring a variable with the (var, const, let) keywords, followed by the name you give to the variable.

    Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.

## Introduction to HTML

 1. What is an HTML attribute?

    HTML attribute is extra information about the element that won't appear in the content.
    Example \<p class="editor-note">MY class work\</p>&nbsp;  
    An attribute should have &nbsp;  
    * A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
    * The attribute name, followed by an equal sign.
    * An attribute value, wrapped with opening and closing quote marks.

 2. Describe the Anatomy of an HTMl element
 HTML elements aren't very useful on their own. Next, let's examine how individual elements combine to form an entire HTML page:&nbsp;
    <span style="color:grey"></span>
 We Have:&nbsp;  
    1. \<!DOCTYPE html>: The doctype. When HTML was young (1991-1992), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML. Doctypes used to look something like this:&nbsp;  
\<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">&nbsp;  
More recently, the doctype is a historical artifact that needs to be included for everything else to work right. \<!DOCTYPE html> is the shortest string of characters that counts as a valid doctype. That is all you need to know!

    2. \<html></html>: The \<html> element. This element wraps all the content on the page. It is sometimes known as the root element.

    3. \<head></head>: The \<head> element. This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers. This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. You will learn more about this in the next article of the series.
    4. \<meta charset="utf-8">: The \<meta> element. This element represents metadata that cannot be represented by other HTML meta-related elements, like \<base>, \<link>, \<script>, \<style> or \<title>. The charset attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain. There is no reason not to set this, and it can help avoid some problems later.
    5. \<title></title>: The \<title> element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.
    6. \<body></body>: The \<body> element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.


 3. What is the Difference between \<article> and \<section> element tags?
 4. What Elements does a “typical” website include?
 5. How does metadata influence Search Engine Optimization?
 6. How is the \<meta> HTML tag used when specifying metadata?

## Miscellaneous

1. What is the first step to designing a Website?
2. What is the most important question to answer when designing a Website?

### Semantics

1. Why should you use an \<h1> element over a \<span> element to display a top level heading?

2. What are the benefits of using semantic tags in our HTML?

### JavaScript

1. Describe 2 things that require JavaScript in the Browser?

2. How can you add JavaScript to an HTML document?

## Questions or Comments (If no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.)

## Things I want to know more about

### Resources used

[How the Web Works. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works),
[Website Design and Process. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like),
[JavaScript Basics. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics),
[Getting started with HTML. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started),
[Document and website structure. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure),
[Metadata in HTML. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML),
[How to start to deign a website. mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding),
[Semantics. mdn web docs_](https://developer.mozilla.org/en-US/docs/Glossary/Semantics),
[JavaScript. mdn web docs_](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
