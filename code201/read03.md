# Code 201 Reading Assigment 3

## Learn HTML

## Ordered and Unordered lists.

1. When should you use an unordered list in your HTML document?

When you have a list of items where the order of the items isn't necessary. 

2. How do you change the bullet style of unordered list items?

There is an HTML attribute for UL called "list-style-type" and you can use a disc, circle or square to change the style of the list.

3. When should you use an ordered list vs an unorder list in your HTML document?

For example if you have a recipe and you wanted to list the ingredients for the recipe above it you could put that list of ingredients in an unordered list because it doesn't matter what order they are only that the user knows they need these items. But then the directions of the recipe could be in an ordered list because you need the recipe to followed in that order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?

You can change the style of the numbers to be roman numbers by using the command \<ol type="i"> or you can change the starting number of an ordered list by using the start attribute like \<ol start="12">


## Learn CSS

## The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

I really don't know how to do what you're asking me here.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

Copied from the reading:

Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.

Padding box: The padding sits around the content as white space; size it using padding and related properties.

Border box: The border box wraps the content and any padding; size it using border and related properties.

Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.


## Learn JS
## Arrays. Operators and Expressions. Conditionals. Loops.

1. What data types can you store inside of an Array?

Tehcnially anything. An array is a list object so you can store names, numbers, anything you could store in a variable.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 
 Yes this is a valid array where the elements all are arrays themselvse which is called a multidemnsional array. You'd access items by using two numbers like:

 people[2][2] which would give you the number 40.

3. List five shorthand operators for assignment in javascript and describe what they do.

Assignment is =

Addition assignment is +=

Subtraction assignment is -=

Multiplication assignment is *=

Division Assignment is /=

4. Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

That would evaluate to "10dog" which in an if statement like this if((a + c) + b) would evaluate to true.


5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

A real world example would be something like 

let a = 5;

if(a>10);

{

  Code stuffs

}

6. Give an example of when a Loop is useful in JavaScript.

When you are waiting on an input from a user and it's needed to continue. You can loop over a prompt until they give you an input that is acceptable.