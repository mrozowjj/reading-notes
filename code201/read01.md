# Codefellows Code 102 - Reading Assignment 1 Notes

## What is Javascript? 

Javascript is a scripting language that let's you add programatic elements to webpages with more power and control than anything HTML can do natively. 

### Compose a short poem describing how HTTP sends data between computers.

hypertext transfer protocol
is an application layer
that runs on top of other layers
in the network stack

### Describe how HTML, CSS, and JS files are “parsed” in the browser.

The browser is written to interpret the HTML, CSS and JS code on a webpage. There's sort of an agrement between the people that made HTML, CSS and JS that this command does X and then the web browser uses the rules defined by each language to create the page using those agreed  upon definitions. They are processed top to bottom.

### How can you find images to add to a Website?

Google image search can help you but you need to look for images that are royality free and not owned by someone else. 

### How do you create a String vs a Number in JavaScript?

JavaScript doesn't care, you don't have to declare a variable as either a string or a number you just assign the variable to the value whether string or number and it will know what it is.

### What is a Variable and why are they important in JavaScript?

An variable is a object container (technically a pointer that points to a place in memory) and it's important because it allows you to have one part of  your code talk to the other part of your code easier by passing the object between functions and other parts of code.



## Metadata in HTML.

### What is an HTML attribute?

An HTML attribute is a property of the page you can set, like "color" or "font."

### Describe the Anatomy of an HTMl element.

Every HTML element must contain and open and closed bracket and then the name of the element along with whatever parameters are needed like \<p>\</p>

### What is the Difference between \<article> and \<section> element tags?

It seems like section is used to block off different portions of a page where an article is used as a sort of specific type of section that adds some special way to segement it from the rest of the page.

### What Elements does a “typical” website include?

A head, heading, body, and footer. Probably some paragraphs and div tags in there.

### How does metadata influence Search Engine Optimization?

Metadata is hidden elements that tag a page with the topics it might be relevent for so that searches can find it.

### How is the \<meta> HTML tag used when specifying metadata?

It's used like this

\<meta name=author" content="Jesse Mrozowski">

Where there's a certain number of parameters you can use with meta.


## Miscellaneous

## How to start to design a Website.

### What is the first step to designing a Website?

Ask yourself what you want the website to accomplish or what information you want the website to have.

### What is the most important question to answer when designing a Website?

"What am I trying to accomplish with this website?"

## Semantics.

### Why should you use an \<h1> element over a \<span> element to display a top level heading?

The H1 element has a semantic value whie the span does not.

### What are the benefits of using semantic tags in our HTML?

It makes it easier to style the page. When you have the different sections you can easily change the way the page looks in a CSS sheet. It also makes it easier to read.

## What is JavaScript?

### Describe 2 things that require JavaScript in the Browser?

Prompting the user for input in a popup.

Doing any kind of math like unit converstion.

### How can you add JavaScript to an HTML document?

You need to either do code inline in the page in a tag like this
\<script>

code

\</script>

Or you can call a seperate file using the following syntac

\<script src="myscript.js">\</script>