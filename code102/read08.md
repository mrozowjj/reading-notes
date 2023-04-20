# Reading Assignment 8 Notes

## What is an expression in JavaScript?

An expression is a unit of code that resolves to a value. Assigning a number to a variable can be expression and a comparison is also expression. So both of these are valid expressions.

```java
x=4;
X>Y;
```


## Why would we use a loop in our code?

You use a loop when you want something to happen multiple times. For example if you wanted a user to input a value and it was necessary to continue executing another portion of your code you could loop on the input statement until you actualy any input or receive input that is formatted correctly.

## When does a for loop stop executing?

A for loop takes an initialization, a condition and an afterthough that looks like this:

for (initialization; condition; afterthought)
for (let i = 0; i < 20; i++)

The foor loop will continue for as long as the condition is true. In the above it will loop for 20 times (the numbers 0-19) and then stop when it reaches 20 as that is no longer less than 20.

## How many times will a while loop execute?

A while loop executes for as long as the statement in the () is true. This means it can execute as few as 0 times or as many as it takes for the statement to become true.