# JavaScript: Error Handling and Debugging


The environment in which your code is running is called **Execution context**. It is created when your code is executed.

JS Engine performs following two steps when executing any code:

1. CREATION PHASE :

   JS Engine parses - run through your code & identifies variables & functions created by code (which will be used in execution phase)
   Setup memory space for Variables & Functions - "Hoisting".

   * Hoisting - before your code is executed, the JS Engine set asides memory space for Var & Function used inside the code. These variables & functions comprise the Execution Context of any function that is be executed. All variables in JS are initially set to undefined.

2. Execution PHASE: pretty simple to understand,

   When the code is executed line-by-line (by JS interpreeter) it can access the variables defined inside Execution Context.
   variable assignment are done in this phase.


A new Execution Context is created whenever function invocation is there.

* Execution Context Stack: What happens when you invoke a function. Take a look at the following example:

Code:

           function b(){

                     }

            function a(){

                  b();
                       }

                    a();


- First, Global Execution Context is going to be created 

- Then execution starts and interpreeter encounters *call to function a()* , and here a new execution context is created pushed on top EC
Stack, so anytime you invoke a function a new EC is created & placed on top of EC Stack.

- So now EC for a() is CREATED interpreeter will execute the code inside a() line-by-line

- Then intrepreeter encounters call to function b(), this creates another EC which is pushed on top or EC stack

- When b() finishes it will be popped-off the stack then a() will finish & all the way down to Global EC


### Error Objects: 

Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

When an Er ror object is created, it will contain the
following properties: 

PROPERTY | DESCRIPTION 
-------|-------
Name  |  Type of execution 
message | Description
fileNumber | Name of the JavaScript file
lineNumber | Line number of error

When there is an error, you can see all of this
information in the JavaScript console I Error console
of the browser. 



There are seven types of built-in error objects in
JavaScript. 

OBJECT | DESCRIPTION 
-------|-------
Error | Generic error - the other errors are all based upon this error
Syntax Error | Syntax has not been followed 
Ref erenceError | Tried to reference a variable that is
not declared/within scope 
TypeError | An unexpected data type that
cannot be coerced 
Range Error | Numbers not in acceptable range
URI Error | encodeURI ().decodeURI(),and
similar methods used incorrectly 
Eval Error | eva l () function used incorrectly

### HOW TO DEAL WITH ERRORS 
There are two things you can do with the errors:

1. DEBUG THE SCRIPT TO FIX ERRORS

   If you come across an error while writing a script, you will need to debug the code, track down the source of the error, and fix it. 

2. HANDLE ERRORS GRACEFULLY
   You can handle errors gracefully using try, catch,
   throw, and f i na 1 ly statements

### BROWSER DEV TOOLS & JAVASCRIPT CONSOLE 

The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be. 

When you are debugging errors, it can help if you
look at the error in more than one browser as they
can show you different error messages. 

You can also just type code into the console
and it will show you a result. 

#### LOGGING DATA TO THE CONSOLE
In javascript, the console is an object which provides access to the browser debugging console.

 The console object provides us with several different methods, like :

1. log()

    Mainly used to log(print) the output to the console. We can put any type inside the log(), be it a string, array, object, boolean etc.

2. error()

   Used to log error message to the console. Useful in testing of code. 
3. warn()

   Used to log warning message to the console. By default the warning message will be highlighted with yellow color.

4. clear()

   Used to clear the console.

5. time() and timeEnd()

  Whenever we want to know the amount of time spend by a block or a function, we can make use of the time() and timeEnd() methods provided by the javascript console object. They take a label which must be same.

6. table()

   This method allows us to generate a table inside a console. The input must be an array or an object which will be shown as a table.

7. count()

   This method is used to count the number that the function hit by this counting method.

8. group() and groupEnd()

    group() and groupEnd() methods of the console object allows us to group contents in a separate block, which will be indented.









