# Putting it all together

## How would you break a mock into a component heirarchy?

* The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components! 



## What is the single responsibility principle and how does it apply to components:
* The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program’s functionality, and it should encapsulate that part. 

## What does it mean to build a ‘static’ version of your application?
* The easiest way is to build a version that takes your data model and renders the UI but has no interactivity. To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props.
## Once you have a static application, what do you need to add?
* Add Your New Site.,
Link to Your GitHub (or supported version-control tool of choice). ,
Authorize Netlify.,
Select Your Repo.,
Configure Your Settings.,
Build Your Site.,

## How can you identify where state needs to live?
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.