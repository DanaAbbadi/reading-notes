# HTML Lists

There are two types of lists in html:
- The ordered list is created with the < ol> element. It lists items using numbeers.

- The unordered list is created with the < ul > element. It lists items using bullets.
 Each item in the list is placed between an opening < li> tag and a closing < /li> tag. (The li stands for list item.)

- < dl> The definition list is created with the < dl> element and usually consists of a series of terms and their definitions. Inside the < dl> element you will usually see pairs of < dt> and < dd> elements.

- Nested Lists : You can put a second list inside an < li> element to create a sublist or nested list.

# HTML Boxes

CSS treats each HTML element as if it lives in its own box. You can set several properties that affect the appearance of these boxes. 

## Box Dimensions: width, height

By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties. To specify the size of a box you use: pixels, percentages, or ems (When you use ems, the size of the box is based on the size of text within it).

- Limiting width: min-width, max-width. min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

- Limiting Height: min-height, max-height. In the same way that you might
want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.

 - Overflowing Content: The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
       1. hidden
           This property simply hides any extra content that does not fit in the box.
       2. scroll
           This property adds a scrollbar to the box so that users can scroll to see the missing content.

## Border, Margin & Padding:

* Border: 
The CSS border properties allow you to specify the style, width, and color of an element's border.
- border-style property specifies what kind of border to display. The following values are allowed:

| dotted | Defines a dotted border|
| dashed | Defines a dashed border|
| solid | Defines a solid border|
| double | Defines a double border|
| groove | Defines a 3D grooved border. The effect depends on the border-color value|
| ridge | Defines a 3D ridged border. The effect depends on the border-color value|
| inset | Defines a 3D inset border. The effect depends on the border-color value|
| outset | Defines a 3D outset border. The effect depends on the border-color value|
| none | Defines no border|
| hidden | Defines a hidden border|

- The border-width property specifies the width of the four borders. The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick.

- The border-color property is used to set the color of the four borders. The color can be set by:
    1. name - specify a color name, like "red"
    2. HEX - specify a HEX value, like "#ff0000"
    3. RGB - specify a RGB value, like "rgb(255,0,0)"
    4. HSL - specify a HSL value, like "hsl(0, 100%, 50%)" transparent
Note: If border-color is not set, it inherits the color of the element.

* Padding
The CSS padding properties are used to generate space around an element's content, inside of any defined borders.With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).

* Margin
The CSS margin properties are used to create space around elements, outside of any defined borders. With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

* Centering Content
If you want to center a box on the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto.

* Hiding Boxes
The visibility property allows you to hide boxes from users but It leaves a space where the element would have been. This property can take two values:
- hidden
  This hides the element.
- visible
  This shows the element.

# JavaScript Switch
The switch statement is used to perform different actions based on different conditions. Use the switch statement to select one of many code blocks to be executed.
This is how it works:
- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.
- If there is no match, the default code block is executed.

![img1]('https://www.bookofnetwork.com/images/javascript-images/JS_switch-syntax_20Sep16_1827.png')

'break' statement is used to come out of switch and continue execution of statement(s) following switch.

# Loops:

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. 

* **For Loop**

    A for loop repeats until a specified condition evaluates to false. <br/>


    ![for](https://tutorial.techaltum.com/images/javascript-loops.jpg) <br/>


    A for statement looks as follows: <br/>
    &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  for ([initialExpression]; [condition]; [incrementExpression]) { <br/>
               &nbsp;  &nbsp;  &nbsp;  statements <br/> 
                &nbsp;  } <br/>
    If the value of condition is true, the loop statements execute. If the value of condition is false, the for loop terminates.        

* **While Loop** <br/>


    A while statement executes its statements as long as a specified condition evaluates to true.


    ![while](https://study.com/cimages/videopreview/videopreview-full/bnip2bj9ee.jpg)


    A while statement looks as follows:<br/>
            &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; while (condition){<br/>
                          &nbsp;  &nbsp;  &nbsp;  statements<br/>
                      &nbsp;   }<br/>
    
    If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.


