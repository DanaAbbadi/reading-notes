# HTML: Links
With HTML, you can easily add hyperlinks to any HTML page. Link team page, about page, or even a test by creating it a hyperlink. To make a hyperlink in an HTML page, use the < a> and < /a> tags, which are the tags used to define the links.

![atag](https://learn-the-web.algonquindesign.ca/topics/html-semantics/html-tag-parts.png)

* Linking to Other Sites
Links are created using the < a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.

* Linking to Other Pages on the Same Site
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

* Relative URLs
Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.
This is especially helpful when
creating a new website or
learning about HTML because
you can create links between
pages when they are only on
your personal computer (before
you have got a domain name and
uploaded them to the web).

- Relative Link Type

Type | Discription
-------|-------
Same Folder| To link to a file in the same folder, just use the file name
Child Folder |For a child folder, use the name of the child folder, followed by a forward slash, then the file name.
Grandchild Folder | Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.
Parent Folder | Use ../ to indicate the folder above the current one, then follow it with the file name.
GrandParent Folder | Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.

* Email Links
To create a link that starts up the user's email program and addresses an email to a specified email address, use the < a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

* Opening Links in a New Window
If you want a link to open in a new window, you can use the target attribute on the opening < a> tag. The value of this attribute should be _blank.

# HTML Layout
In this section we are going to look at how to control where each element sits on a page and how to create attractive page layouts.

### Key Concepts in Positioning Elements

* Building Blocks
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box. **Block-level boxes** start on a new line and act as the main building blocks of any layout examples include:< h1> < p> < ul> < li>, while **inline boxes** flow between surrounding text examples include: < img> < b> < i>.

* Containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

It is common to group a number of elements together inside a < div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The < div> element that contains this group of elements is then referred to as the *containing element*.

* Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

- **Normal flow**
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

- **Relative Positioning**
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

- **Absolute positioning**
This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

* Floating Elements
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.

* Clearing Element
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:
   - left
      The left-hand side of the box should not touch any other elements appearing in the same
      containing element.
   - right
      The right-hand side of thebox will not touch elements appearing in the same containing element.
   - both
      Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
   - none
      Elements can touch either side.

# JavaScript Functions

## Functions

A function is a group of statements that together perform a specific task. If different parts of a script repeat the same task, you can
reuse the function. To use the function in your code, you need to "call" it.
Advantages of using functions:

   - Code Re-usability
   - Develop an application in module format.
   - Easily to debug the program.
   - Code optimization: No need to write lot of code.

A JavaScript function is declared by with the function keyword, followed by a name, followed by parentheses ().
The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)
The code to be executed, by the function, is placed inside curly brackets: {}.

![fun](https://www.code-morning.com/wp-content/uploads/2016/09/Function1-300x154.png)

When JavaScript reaches a return statement, the function will stop executing.

# 6 Reasons for Pair Programming
Pair programming is an agile software development technique in which two programmers work together at one workstation. One, the driver, writes code while the other, the observer or navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently.

1. Greater efficiency
   Pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging, it also enhances technical skills, team communication, and even enjoyability of coding in the workplace.

2. Engaged collaboration
   When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. 

3. Learning from fellow students
    Developers in a pairing have different skill sets. If one programmer is more experienced in a certain skill, they can teach a student who is less familiar with that area.

4. Social skills
   Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills. 

5. Job interview readiness
   The ability to work with and learn from others and stellar communication skills are as (or more!) important to a company than specific technical skills. Pair programming strengthens all of those skills.

6. Work environment readiness
   Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.




