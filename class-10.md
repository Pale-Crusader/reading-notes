# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

> From the Duckett JS book:

> JavaScript book, Ch. 10, “Error Handling & Debugging

* Javascript is hard to learn and everyone makes mistakes.
* ways to resolve this involve using the console and deve tools. 
* there's a series of common problems 
* there's code that deals with errors gracefully

### order of operations 
* it is important that things are executed in the proper order. This is known as order of execution.
* execution context. Javascript uses and interpretor that understands execution contexts. There is one global execution context plus each function creates a new execution context. The difference between these affects the scope variable. 
    * global context is available to everything and is defined not in a function. 
    * function context; the variables apply only within the function. 
    * evaluation context; is executed like code in an internal function called eval which is not covered by the book. 
* the stack; the Javascript interpreter reads one line of code at a time and when data from another function is needed it stacks that function on top of the current task. 
* execution context and hoisting; when the script enters a new execution context there are two phases: prepare and execute
    * preparing looks through the scopes finds the appropriate variables, functions, and arguements. This is where it pulls the information from previously declared functions and does the aforementioned stacking.
    * execute: this is where it runs the code that it has stacked up in the previous step.  

    ### understanding scope 
    * things inside a function scope can see global scope but global scope can only see what is returned from inside of a function or if a function has altered a global variable. 

    ### understanding errors 
    * we can find errors in the console. also VS code will let us know errors. 
    * error objects can help you find where your mistakes are and the browser has tools to find them in the aforemention console like we have been doing in class. 
    * types of errors; syntax error, reference error, eval error, uri error, type error, range error, error, nan
    * knowing the types of errors will help you understand what might be causing them and where to look in your code. It is best to work on small pieces of code and check functionality often.
    * we've been doing a lot of this console logging and troubleshooting in class that the book talks about over the next few pages so I am comfortable noting it like this. 
    * new concept; break points (pg 476) it is possible to get the values that are stored by Javascripts and that is an important tool in debugging. this can be done conditional or multiple times through the code. There is also a debugger keyword pg 479