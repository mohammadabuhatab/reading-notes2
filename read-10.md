
JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.


Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined
2. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

<hr>

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

<hr>

## ERROR OBJECTS CONTINUED
* Syntax Error
* Reference Error
* Eval Error
* URI Error
* Type Error
* Range Error
* Error
* NaN

<a href="README.md">HOME</a>