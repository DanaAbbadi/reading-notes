# CSS Layout

![css](https://www.tutorialrepublic.com/lib/images/css-illustration.png)

### Controlling the position of elements

#### Key Concepts in Positioning Elements

 * Building Blocks

  CSS treats each HTML element as if it is in its
  own box. This box will either be a block-level
  box or an inline box.
  **Block-level** boxes start on a new line and act as the main building blocks
  of any layout, while **inline boxes** flow between surrounding text. 

  You can control how much space each box takes up by setting the width of the
  boxes (and sometimes the height, too). To separate boxes, you can use
  borders, margins, padding, and background colors. 

* Containing Elements

  If one block-level element sits inside another
  block-level element then the outer box is
  known as the containing or parent element.
  
  -Note: It is common to group a number of elements together inside a < div>
         (or other block-level) element.

#### Controlling the Position of Elements       

 CSS has the following positioning schemes that allow you to control
 the layout of a page: normal flow, relative positioning, and absolute
 positioning. You specify the positioning scheme using the position
 property in CSS. You can also float elements using the float property.

 1. Normal 
 
    Every block-level element
    appears on a new line, causing
    each item to appear lower down
    the page than the previous one. 

     Since this is the default
     way in which browsers treat
     HTML elements, you do not
     need a CSS property to indicate
     that elements should appear
     in normal flow, but the syntax
     would be:   position: static;

 2. Relative positioning 

    This moves an element from the
    position it would be in normal
    flow, shifting it to the top, right,
    bottom, or left of where it
    would have been placed. This
    does not affect the position of
    surrounding elements; they stay
    in the position they would be in
    in normal flow.

    You then use the offset
    properties (top or bottom and
    left or right) to indicate how
    far to move the element from
    where it would have been in
    normal flow.



 3. Absolute positioning
 
    This positions the element
    in relation to its containing
    element. It is taken out of
    normal flow, meaning that it
    does not affect the position
    of any surrounding elements 

    When the position property
    is given a value of absolute,
    the box is taken out of normal
    flow and no longer affects the
    position of other elements on
    the page. (They act like it is not
    there.) 


 4. Fixed Positioning

    This is a form of absolute
    positioning that positions
    the element in relation to the
    browser window, as opposed
    to the containing element.
    Elements with fixed positioning
    do not affect the position of
    surrounding elements and they
    do not move when the user
    scrolls up or down the page.

 5. Floating Elements

    Floating an element allows
    you to take that element out
    of normal flow and position
    it to the far left or right of a
    containing box. The floated
    element becomes a block-level
    element around which other
    content can flow.

    Anything else that sits inside
    the containing element will
    flow around the element that is
    floated.

  - Clearing Floats:  

     The clear property allows you
     to say that no element (within
     the same containing element)
     should touch the left or righthand sides of a box. It can take
     the following values:

     1. left

       The left-hand side of the box
       should not touch any other
       elements appearing in the same
       containing element.

     2. right

       The right-hand side of the
       box will not touch elements
       appearing in the same containing
       element.

     3. both

       Neither the left nor right-hand
       sides of the box will touch
       elements appearing in the same
       containing element.

     4. none

       Elements can touch either side.

 

