# Reading Assignment 7 - Programming with JavaScript    

## What is control flow?

The control flow is the order in which the computer executes a statement in a script. It is like the order of operations in math. For example in an if(confirm()){do the thing} statement the confirm() needs to be executed before it can do whatever is in the if statement

## What is a JavaScript function?

A JavaScript function is a block of code designed to perform a specific task. For example you could create a function to convert between metric and imperial units. Functions are a tenant of object oriented programming.

## What does it mean to invoke - or call - a function?

It means you are executing that block of code on command. If you have a function to convert between metric and imperial invoking or calling the fuction would be how you use that function to actually perform the conversion.

## What are the parenthesis () for when you define a function?

The paranthesis is where you put any arguments you want in a funciton. Using the example of converting units we might want to pass the arguments for the value we want to convert, the unit the value is in and the unit we desire the value to be in. So hypotethcially we could have:

```java

    convert(value, ValueUnit, DesiredUnit);
    convert(10, centimeters, inches);

```