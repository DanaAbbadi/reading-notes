# HTML 
![html](https://www.edureka.co/blog/wp-content/uploads/2019/06/What-is-HTML.jpg)

All websites use HTML and CSS, but content
management systems, blogging software, and
e-commerce platforms often add a few more
technologies into the mix.

HTML stands for Hyper Text Markup Language and it is the standard markup language for creating web pages and web applications. It is used to describe the structure of Web pages using markup. → A markup language is a computer language that is used to apply layout and formatting conventions to a text document. Markup language makes the text more interactive and dynamic. It can turn text into images, tables, links, etc.

The HTML code is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.
The figure bellow shows the recommended minimal skeleton of an HTML5 document:

![main](https://www.oreilly.com/library/view/learning-web-design/9781449337513/httpatomoreillycomsourceoreillyimages2257981.png)

1. Document type declaration (also called DOCTYPE declaration) that identifies this document as an HTML5 document.
2. The entire document is contained within an html element. The html element is called the root element because it contains all the   elements in the document.
3. Within the html element, the document is divided into a head and a body. The head element contains descriptive information about the document itself, such as its title, the style sheet(s) it uses, scripts, and other types of “meta” information.
4. The meta elements within the head element provide information about the document itself.
5. Also in the head is the mandatory title element. According to the HTML specification, every document must contain a descriptive title.
6. the body element contains everything that we want to show up in the browser window.

### Writting comments:

If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
<!-- comment goes here -->
It is a good idea to add comments to your code because, no matter how familiar you are with the page at the time of writing it, when you come back to it later (or if someone else needs to look at the code), comments will make it much easier to understand.

### Id Attribute
Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Giving an element a
unique identity allows you to
style it differently than any other
instance of the same element
on the page. Also,  id attributes can be
used to allow the script to work
with that particular element.
The id attribute is known as a
global attribute because it can
be used on any element.

### Class Attribute
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page. 


### Grouping Text & Elements In a Block
The <div> tag:
The <div> element allows you to
group a set of elements together
in one block-level box.
For example, you might create
a <div> element to contain all
of the elements for the header
of your site (the logo and the
navigation), or you might create
a <div> element to contain
comments from visitors.

The <span> tag:
The <span> element acts like
an inline equivalent of the <div>
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements
The most common reason why
people use <span> elements
is so that they can control the
appearance of the content of
these elements using CSS.

# JavaScript:

 ![java](https://hackernoon.com/hn-images/1*bxEkHw1xewxOFjmGunb-Cw.png)

 JavaScript is among the most powerful and flexible programming languages of the web. It powers the dynamic behavior on most websites. This is where we can change how the page behaves, adding interactivity. 

**Linking to a JavaScript file from an HTML page**
 You can include JavaScript in your HTML in two ways:
 * Writing the code in your HTML
 * Including it as a link to an external file

 But it is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.

 **Writting a Script** 
 
 A script is a series of instructions that a computer can follow to achieve a goal.Therefor to write a script, you need to first state your goal and then list the
tasks that need to be completed in order to achieve it. A helpful way to achieve thet is by going through three stages, they are:
 
       1. Define the goal. 
       2. Design your script; by drawing flowcharts and then derive steps out of it.
       3. Code each step.  

       
  * *COMMENTS*:
    You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. There are two ways to add a comment:
    1. Single comment: by adding  //  
    2. Multi-line comment: by writting your comment in between  /*   */  
              

  * *VARIABLE*:
  
    ![varsec](https://miro.medium.com/max/734/1*IKWdLy1iqPGcVgaYZDlhvg.png)

     variables are used to store data values. JavaScript uses the **var**  keyword to declare variables. An equal sign is used to assign values to variables.   
            For example: var sum = 0 ;

     Multiple data types can be stored in variables,  JavaScript distinguishes between numbers, strings, and true or false values. The example bellow shows how to store different data types in var :
                
                 var pi = 3.14;
                 var person = "John Doe";
                 var answer = 'Yes I am!';        
     






















