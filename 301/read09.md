# FUNCTIONAL PROGRAMMING

## What is functional programming?

* In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. … When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects.

## What is a pure function and how do we know if something is a pure function?

* The definition of a pure function is: The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.

## What are the benefits of a pure function?

* In computer programming, a pure function is a function that has the following properties: The function return values are identical for identical arguments (no variation with local static variables, non-local variables, mutable reference arguments or input streams)

## What is immutability?

* immutable object is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created. In some cases, an object is considered immutable even if some internally used attributes change, but the object’s state appears unchanging from an external point of view. For example, an object that uses memoization to cache the results of expensive computations could still be considered an immutable object.

## What is Referential transparency?

* properties of parts of computer programs. An expression is called referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program’s behavior. This requires that the expression be pure, that is to say the expression value must be the same for the same inputs and its evaluation must have no side effects. An expression that is not referentially transparent is called referentially opaque

----

## What is a module?

* Modules are small units of independent, reusable code that is desired to be used as the building blocks in creating a non-trivial Javascript application. Modules let the developer define private and public members separately, making it one of the more desired design patterns in JavaScript paradigm.

## What does the word ‘require’ do?

* require() is used to consume modules. It allows you to include modules in your app. You can add built-in core Node. js modules, community-based modules (node_modules), and local modules too.

## How do we bring another module into the file the we are working in?

* To include functions defined in another file in Node. js, we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation.
