
# HTML Tags:
HTML contains lots of predefined tag. Some of them are described below:

* Heading
The < h1 > to < h6 > tags are used to define HTML headings.

< h1 > defines the most important heading. < h6 > defines the least important heading.

* Paragraphs 
The < p> tag defines a paragraph. By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

* Bold & Italic
- < b > tag :By enclosing words in the tags < b > and </ b > we can make characters appear bold.
- < i > tag :By enclosing words in the tags < i > and </ i > we can make characters appear italic.

 * Line Breaks & Horizontal Rules
 - < br /> Tag : The browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag < br />.
 - < hr /> Tag :To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the < hr /> tag.

 ### Semantic Markup

 Semantic HTML or semantic markup is HTML that introduces meaning to the web page rather than just presentation. For example, a <p> tag indicates that the enclosed text is a paragraph. This is both semantic and presentational because people know what paragraphs are, and browsers know how to display them. The following tags are examples of semantic HTML:

 - < strong> tag :
The use of the < strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a < strong>
element in bold.

- < em> tag :
The < em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an < em> element
in italic.

- < blockquote> tag :
The < blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the < p> element is still
used inside the < blockquote>
element. 

- < abbr> tag : defines an abbreviation or an acronym, like "HTML", "Mr.", "Dec.", "ASAP", "ATM". For example: 
The < abbr title="World Health Organization">WHO</ abbr> was founded in 1948.

# Interducing CSS  
![CSS](https://www.tutorialrepublic.com/lib/images/css-illustration.png)
CSS stands for Cascading Style Sheets and almost all webpages and user interfaces written with HTML use it, since CSS is a style sheet language that adds styling and formatting to documents written in a markup language. Adding CSS to your HTML code will make make our websites unique and attractive.

## How to link CSS to HTML code
You can link it in three ways:
* External - by using an external CSS file, Using the <link> element.
* Internal - by using a <style> *element* in the <*head*> *section*
* Inline - by using the style attribute in HTML elements

## CSS Syntax
![CSSS](https://www.tutorialrepublic.com/lib/images/css-selector.png)

As you can see, The *selector* specifies which element or elements in the HTML page the CSS rule applies to. While the *declarations* within the block determines how the elements are formatted on a webpage. Each declaration consists of a property and a value separated by a colon (:) and ending with a semicolon (;), and the declaration groups are surrounded by curly braces {}. The property is the style attribute you want to format; for example you can change the padding, color, font , etc. 

## CSS Selectors

In CSS, selectors are patterns used to select the element(s) you want to style. Selectors are one of the most important aspects of CSS as they allow you to target specific elements on your web page in various ways so that they can be styled.
There are several types of selectors in CSS, the table below mentions the common used ones:

| Selector | description |
| ---:| ---:|
|Element Type Selectors   | matches all instance of the element in the document with the corresponding element type name. | 
| Id Selectors  | The id selector is used to define style rules for a single or unique element  |
| Class Selectors  | Selects all elements set within its class attribute |


# Basic JavaScript Instructions

![prog](https://res.cloudinary.com/springboard-images/image/upload/q_auto,f_auto,fl_lossy/wordpress/2019/08/sb-blog-java.png)

* Statements
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 

![prog1](https://i1.wp.com/pandabunnytech.com/wp-content/uploads/2018/11/types-of-statements-in-javascript-e1543313160116.png)

* Comments
    You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. There are two ways to add a comment:
    1. Single comment: by adding  //  
    2. Multi-line comment: by writting your comment in between  /*   */  
              
* Variable
  
    ![varsec](https://miro.medium.com/max/734/1*IKWdLy1iqPGcVgaYZDlhvg.png)

     variables are used to store data values. JavaScript uses the **var**  keyword to declare variables. An equal sign is used to assign values to variables.   
            For example: var sum = 0 ;

     Multiple data types can be stored in variables,  JavaScript distinguishes between numbers, strings, and true or false values. The example bellow shows how to store different data types in var :
                
                 var pi = 3.14;
                 var person = "John Doe";
                 var answer = 'Yes I am!';    

* Array

- JavaScript arrays are used to store multiple values in a single variable. An array is a special variable, which can hold more than one value at a time. 
To creat an Array: 
var cars = ["Saab", "Volvo", "BMW"];

- Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one). 

* Comparsion Operators 

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.
The following table describes the comparison operators:

 | Operator | Description |
|----: |---:|
| Equal (==)   |    Returns true if the operands are equal.   |
| Not equal (!=)   |  Returns true if the operands are not equal.     |
| Strict equal (===)    |   Returns true if the operands are equal and of the same type.    |
| Strict not equal (!==)    | Checks if the operands are of the same type but not equal, and vise versa |
| Greater than (>)    |   Returns true if the left operand is greater than the right operand.    |
| Greater than or equal (>=)    |  Returns true if the left operand is greater than or equal the right |

* Logical Operators
Logical operators are typically used with Boolean (logical) values, The logical operators are described in the following table.

![truth](https://www.startertutorials.com/corejava/wp-content/uploads/2014/10/Logical-operators-table.jpg)

* Conditional Statements

- if statment : we use the if statement to specify a block of JavaScript code to be executed if a condition is true.
The syntax for a basic if statement is as follows :

if (expression) {
   Statement(s) to be executed if expression is true
}

- if...else statement :
The 'if...else' statement is the next form of control statement that allows JavaScript to execute statements in a more controlled way. The JavaScript expression is evaluated. If the resulting value is true, the given statement(s) in the ‘if’ block, are executed. If the expression is false, then the given statement(s) in the else block are executed.

# Git Commit massage

- What is a commit message?
The commit command is used to save changes to a local repository after staging in Git. However, before you can save changes in Git, you have to tell Git which changes you want to save as you might have made tons of edits. A great way to do that is by adding a commit message to identify your changes.

- How to write good commit messages
There are several conventions used by different teams and developers to write good commit messages. You can apply The seven rules of a great Git commit message:

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how


