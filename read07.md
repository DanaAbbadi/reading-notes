
# HTML Tables

A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

* Basic Table Structure
- < table>
The < table> element is used
to create a table. The contents
of the table are written out row
by row.

- < tr>
You indicate the start of each
row using the opening < tr> tag.
(The tr stands for table row.)
It is followed by one or more
< td> elements (one for each cell
in that row).

- < td>
Each cell of a table is
represented using a < td>
element. (The td stands for
table data.)

- < th>
The < th> element is used just
like the < td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.) 


# JavaScript : Object Constructors
Object: Object is the collection of related data or functionality in the form of key. This functionalities are usually consists of several functions and variables.

Sometimes we need a "blueprint" for creating many objects of the same "type". The way to create an "object type", is to use an object constructor function. In the example above, function Person() is an object constructor function. Objects of the same type are created by calling the constructor function with the **new** keyword. For example:

!(img)[/mnt/c/Users/STD/ltuc/201/reading-notes/img/Capture.PNG]
* The this Keyword
In JavaScript, the thing called *this* is the object that "owns" the code. The value of this, when used in an object, is the object itself. In a constructor function this does not have a value. It is a substitute for the new object. The value of this will become the new object when a new object is created.

* Adding a Property to an Object
Adding a new property to an existing object is easy: for example

objectname.property = "value";

The property will be added to myFather. Not to myMother. (Not to any other person objects).

* Adding a Method to an Object
Adding a new method to an existing object is easy: for example

objectname.name = function () {
  code
};





# Domain Modeling
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

* Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function. In class-based object-oriented programming, a constructor is a special type of subroutine called to create an object. It prepares the new object for use, often accepting arguments that the constructor uses to set required member variables.

* Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.












