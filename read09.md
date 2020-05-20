# HTML Forms

### Form Controls

There are several types of form controls that
you can use to collect information from visitors
to your site.

* ADDING TEXT:
1. Text input (single-line) :

Used for a single line of text such
as email addresses and names.

2. Password input : 
Like a single line text box but it
masks the characters entered.

3. Text area (multi-line) :
For longer areas of text, such as
messages and comments.

* Making Choices:

1. Radio buttons
For use when a user must select
one of a number of options.

2. Checkboxes
When a user can select and
unselect one or more options.

3. Drop-down boxes
When a user must pick one of a
number of options from a list


* Submitting Forms:
1. Submit buttons
To submit data from your form
to another web page

2. Image buttons
Similar to submit buttons but
they allow you to use an image


### How Forms Work

1. A user fills in a form and then presses a button
to submit the information to the server.

2. The name of each form
control is sent to the
server along with the
value the user enters or
selects.

3. The server processes
the information using a
programming language
such as PHP, C#, VB.net,
or Java. It may also store
the information in a
database.

4. The server creates a new
page to send back to the
browser based on the
information received.


### Form Elements

* The HTML < form> element defines a form that is used to collect user input:
An HTML form contains form elements.
Form elements are different types of input elements, like: text fields, checkboxes, radio buttons, submit buttons, and more.

* The < input> Element
The < input> element is the most important form element.
The < input> element is displayed in several ways, depending on the type attribute.

* Text Fields : 
< input type="text"> defines a single-line input field for text input.

# Lists and Tables

### Lists CSS styles:

#### Bullet Point Styles

The list-style-type property
allows you to control the shape
or style of a bullet point.

* Unordered Lists
For an unordered list you can use
the following values:
 - none
 - disc
 - circle
 - square

* Ordered Lists
For an ordered (numbered) list
you can use the following values:
- decimal
1 2 3
- decimal-leading-zero
01 02 03
- lower-alpha
a b c
- upper-alpha
A B C
- lower-roman
i. ii. iii.
- upper-roman
I II III


#### Images for Bullets (list-style-image)

You can specify an image to act
as a bullet point using the
list-style-image property.

Syntax: list-style-image: url("images/star.png")

### Tables

The table bellow shows some of the CSS elements to style tables:

 CSS border property | to define a border
CSS border-collapse property | to collapse cell borders
CSS padding property | to add padding to cells
CSS text-align property |  to align cell text
CSS border-spacing property | to set the spacing between cells
colspan attribute | to make a cell span many columns
rowspan attribute | to make a cell span many rows
 id attribute | to uniquely define one table


# JavaScript Events

Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user clicks a button on a webpage, you might want to respond to that action by displaying an information box. 

### HOW EVENTS TRIGGER JAVASCRIPT CODE
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 

* THREE WAYS TO BIND AN EVENT TO AN ELEMENT:

Event handlers let you indicate which event you
are waiting for on any particular element.
There are three types of event handlers.

1. HTML EVENT HANDLERS

Early versions of HTML included
a set of attributes that could
respond to events on the
element they were added to.
The attribute names matched
the event names. Their values
called the function that was to
run when that event occurred.
This method of event handling
is no longer used because it is
better to separate the JavaScript
from the HTML. You should use
one of the other approaches
shown on this page instead.

2. TRADITIONAL DOM EVENT HANDLERS

They are considered better than
HTML event handlers because
they let you separate the
JavaScript from the HTML.
Support in all major browsers is
very strong for this approach.
The main drawback is that you
can only attach a single function
to any event. 
As a result of this limitation, if
more than one script is used on
the same page, and both scripts
respond to the same event, then
one or both of the scripts may
not work as intended.

3. DOM LEVEL 2 EVENT LISTENERS

Event listeners were introduced
in an update to the DOM
specification (DOM level 2)
They are now the favored way of
handling events. 

























