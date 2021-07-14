# Error handiling and debugging.
When you are writing JavaScript, do not expect to write it perfectly the first time. 
Programming is like problem solving: you are given a puzzle and not only do you have to solve 
it, but you also need to create the instructions that allow the computer to solve it. too. 
When writing a long script, nobody gets everything right in their first attempt. The error 
messages that a browser gives look cryptic at first, but they can help you determine what 
went wrong in your JavaScript and how to fix it.   

* ORDER OF EXECUTION   
To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run.

---

* EXECUTION CONTEXTS   
The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.

* EXECUTION CONTEXT   
Every statement in a script lives in one of three 
execution contexts:
1. GLOBAL CONTEXT 
Code that is in the script, but not in a function. 
There is only one global context in any page. 
2.  FUNCTION CONTEXT 
Code that is being run within a function. 
Each function has its own function context. 
3. EVAL CONTEXT (NOT SHOWN) 
Text is executed like code in an internal function 
called eva l {).

* VARIABLE SCOPE  

The first two execution contexts correspond with the 
notion of scope.  
1. GLOBAL SCOPE 
If a variable is declared outside a function, it can 
be used anywhere because it has global scope. 
If you do not use the var keyword when creating 
a variable, it is placed in global scope. 
2. FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, 
it can only be used within that function. This is 
because it has function-level scope.

* EXECUTION CONTEXT & HOISTING  
1. PREPARE 
* The new scope is created 
* Variables, functions, and arguments are created 
* The value of the this keyword is determined
2. EXECUTE 
* Now it can assign values to variables 
* Reference functions and run their code
* Execute statements  

---

* UNDERSTANDING SCOPE   
In the interpreter, each execution context has its own va ri ables object. 
It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's v a ri ables object. Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within. So, for each execution context, the scope is the current execution context's variables object, plus the variables object for each parent execution context. 

* UNDERSTANDING ERRORS   
If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. 
If you are anticipating that something in your code 
may cause an error, you can use a set of statements 
to handle the error. This is important because if the error is not handled, the script will just stop processing and the user will not know why. So exception-handling code should inform users when there is a problem.  

---
* ERROR OBJECTS  
Error objects can help you find where your mistakes are 
and browsers have tools to help you read them.  

* HOW TO DEAL WITH ERRORS    
1. DEBUG THE SCRIPT TO FIX ERRORS   
If you come across an error while writing a script 
(or when someone reports a bug), you will need to 
debug the code, track down the source of the error, 
and fix it. 
You will find that the developer tools available in 
every major modern browser will help you with 
this task. In this chapter, you will learn about the 
developer tools in Chrome and Firefox. (The tools in 
Chrome are identical to those in Opera.) 
IE and Safari also have their own tools (but there is 
not space to cover them all). 
2. HANDLE ERRORS GRACEFULLY   
You can handle errors gracefully using try, catch, 
throw, and f i na 1 ly statements. 
Sometimes, an error may occur in the script for a 
reason beyond your control. For example, you might 
request data from a third party, and their server 
may not respond. In such cases, it is particularly 
important to write error-handling code. 
In the latter part of the chapter, you will learn how to 
gracefully check whether something will work, and 
offer an alternative option if it fails.