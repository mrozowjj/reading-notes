# Code 201 Reading Assigment 7

## Domain Modeling

1. Explain why we need domain modeling.

A conceptural model that is well articulated can be useful to validate how well you understand the problem.

## HTML Table Basics

1. Why should tables not be used for page layouts?

Using layout tables reduces accessiblity for visually impared users. Tables make tags very difficult.
Tables are also not automatically responsive.

2. List and describe 3 different semantic HTML elements used in an HTML <table>.

\<table> makes the table
\<tr> makes the table row
\<col> makes a new column

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

A constructor is a function called using the new keyword. It will create a new object, bind **this** to the new object so you can refer to **this** in your constructor code, run the code in the constructor and return the new object. Using it allows you to easily create multiple similar objects.

2. How does the term this differ when used in an object literal versus when used in a constructor?

In a constructor it's binded to the new object vs a literal where it can only be used inside an object. 

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question

Inheritance is the idea an object will have the same properties of whatever object it is defined as. For example if you create a class that's just called bag and define it as something that can hold a finite amount of objects and then you could create another fuction called bookbag and it would inheritat the ability to to hold a certain number of objects. You can specify that the bookbag objects would all be books and put a different limit on the objects it can hold.