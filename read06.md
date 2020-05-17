# Problem Domain

Problem domain (or problem space) is an engineering term referring to all information that defines the problem and constrains the solution (the constraints being part of the problem). It includes the goals that the problem owner wishes to achieve, the context within which the problem exists, and all rules that define essential functions or other aspects of any solution product. It represents the environment in which a solution will have to operate, as well as the problem itself.

The 'problem domain', then, is the user-requirements, user stories, use-cases. It's what you're getting paid to achieve. It isn't necessarily what the client tells you, either... a software developer often must go to great teeth-pulling efforts to determine the problem domain.

### Programming is easy if you understand the problem domain
 understanding the problem is the most critical piece to the equation. It is very difficult to solve a problem before you know the question.  

*What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- Make the problem domain easier
- Get better at understanding the problem domain

 As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.  Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.  It is much more expensive and time consuming to do things over than it is to do them right the first time.


 # JavaScript: Object

Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.

An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.


Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.
An object can be created with figure brackets {…} with an optional list of properties. A property is a “key: value” pair, where a key is a string (also called a “property name”), and value can be anything.

In an object, variables and functions take on new names:

- IN AN OBJECT: VARIABLES BECOME KNOWN AS **PROPERTIES**,
 Properties tell us about the object.

- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS **METHODS**,
Methods represent tasks that are associated with
the object.  

## Creating objects

* Literal Notation

A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.

The following demonstrates an example object literal:

var myObject = {
    sProp: 'some string value',
    numProp: 2,
    bProp: false
};

- Object Literal Syntax:
Object literals are defined using the following syntax rules:

1. A colon separates property name from value.
2. A comma separates each name-value pair from the next.
3. There should be no comma after the last name-value pair.


- You can access object properties in two ways:

1. dot notation: objectName.propertyName


2. bracket notation: objectName["propertyName"]

## Document Object Model (DOM)
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window. 

###  ACCESSING ELEMENTS
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 

* METHODS THAT RETURN A SINGLE ELEMENT NODE: 

1. getElementByld( 1 id 1)
Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable.

2. querySel ector( 1 css selector')
Uses CSS selector syntax that would select one or more elements .
This method returns only the first of the matching elements.

* METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST): 

1. getEl ementsByClassName( 1 class 1 )
Selects one or more elements given the value of their cl ass attribute.
The HTML must have a cl ass attribute for it to be selectable.
This method is faster than querySe 1ectorA11 () .


2. getEl ementsByTagName( 1 tagName 1 )
Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ().

3. querySelectorAll ( 1 css select or•)
Uses CSS selector syntax to select one or more elements and returns all
of those that match.




















