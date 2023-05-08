# Code 201 Reading Assigment 6

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

An object is a container with data in it. It can be as much or as little data as it needs.

2. What are some advantages to creating object literals?

Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array

3. How do objects differ from arrays?

An object is sometimes called an associated array because it's very similar. The difference is you can access ojbect items using the name instead of the index number.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

 If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```
In this code this refers to dog and the advantage of using this is you don't need to rewrite the object code every time you create one. Doesn't seem important if you're doing object literals but should be useful when using functions.

## Introduction To The DOM

1. What is the DOM?

Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.

2. Briefly describe the relationship between the DOM and JavaScript.

from: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.