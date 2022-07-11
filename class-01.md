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

     \<!DOCTYPE html>
       \<html>
          \ <head>
              \ <meta charset="utf-8">
              \ <title>My test page</title>
          \</head>
              \<body>
                  \ <p>This is my page</p>
               \</body>  
        \</html>
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
    Article \<article>element encloses a block of related content that makes sense on its own without the rest of the page.
    Section \<section>element is more for grouping together a single part of the page that constitutes one single piece of functionality or a theme. It's considered best practice to begin each section with a heading; also note that you can break \<article>s up into different \<section>s, or \<section>s up into different \<article>s, depending on the context.

 4. What Elements does a “typical” website include?
    * Paragraphs.
    * Form controls including radio buttons, edit fields, check boxes, combo boxes, list boxes, and buttons.
    * Links.
    * Numbered and bulleted lists.
    * Headings.
    * Images.
    * Tables.
    * Regions.

 5. How does metadata influence Search Engine Optimization?
    Your website metadata consists of a page title and meta description for every page. These provide search engines like Google with important information about the content and purpose of each individual page on your website, and help them determine whether your website is relevant enough to display in search results.
    Using metadata boosts your SEO efforts because it's written in the search engine's language. This helps search engines better understand the topic of your webpages and content. It also helps them display more relevant results to searchers.

 6. How is the \<meta> HTML tag used when specifying metadata?

    Meta tag defines about the metadata in an html document, meta tags
     always go inside the head tag .It is typically  used to specify page description, character set, keywords, author of the document and viewport settings. The information we store in the meta tag are not displayed directly in the website but are read by the bots of the browsers and using this our website will be positioned in the search list of the search result. To rank our website, the keyword content most importantly should be 'search engine optimised'(S.E.O).

     EXAMPLE:
     <head lang="en">
        <meta http-equiv="content-language" content="en">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="keywords" content="website, blog, foo, bar">
        <meta name="author" content="John Doe">
        <meta name="publisher" content="John Doe">
        <meta name="copyright" content="John Doe">
        <meta name="description" content="This short description describes my website.">
        <meta name="page-topic" content="Media">
        <meta name="page-type" content="Blogging">
        <meta name="audience" content="Everyone">
        <meta name="robots" content="index, follow">
    <title>My website title</title>
    </head>

## Miscellaneous

1. What is the first step to designing a Website?
    Before doing anything, you need some ideas. What should your website actually do? A website can do basically anything, but, for your first try, you should keep things simple. We'll start by creating a simple webpage with a heading, an image, and a few paragraphs.

    To begin, you'll need to answer these questions:

    1. What is your website about?

    2. What information are you presenting on the subject?

    3. What does your website look like

    Note: Complex projects need detailed guidelines that go into all the details of colors, fonts, spacing between items on a page, appropriate writing style, and so on. This is sometimes called a design guide, design system, or brand book, and you can see an example at the Firefox Photon Design System

2. What is the most important question to answer when designing a Website?
    What exactly do I want to accomplish?

### Semantics

1. Why should you use an \<h1> element over a \<span> element to display a top level heading?

    \<h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

    \<span> This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.

2. What are the benefits of using semantic tags in our HTML?

    Some of the benefits from writing semantic markup are as follows:
    * Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
    * Screen readers can use it as a signpost to help visually impaired users navigate a page
    * Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
    * Suggests to the developer the type of data that will be populated
    * Semantic naming mirrors proper custom element/component naming

### JavaScript

1. Describe 2 things that require JavaScript in the Browser?

    Games, animated 2D and 3D graphics, comprehensive database-driven apps, API

2. How can you add JavaScript to an HTML document?

    You can add JavaScript to an HTML document using the \<script> tag.

## Questions or Comments (If no questions provided, summarize and explain this topic via an analogy from your previous work or home experience.)

Question: How to start a design structure for a website keep a schudule on task keep it simple and not go over board and over whelm and never start.

## Things I want to know more about

I would like to know more about start to design a website. Like the structure to keep a schudule of getting things done.

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
