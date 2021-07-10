# Problem Domain, Objects, and the DOM

---

### WHAT IS AN OBJECT?
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

#### CREATING· OBJECTS USING LITERAL NOTATION
This object represents a hotel. It has five properties and one method. 
The object is in curly braces. It is stored in a variable called hotel . 
```
var hotel = {
name:'Quay',
rooms:40,
booked:25,
gym:true.
roomTypes:['twin','double','suite'],

checkAvilability: function(){
    return this.rooms - this.booked;
}

}
```
---
### Document Object Model (DOM)
The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

* The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. 
It is implemented by all major browser makers, and covers two primary areas:
1. MAKING A MODEL OF THE 
HTM L PAGE 
When the browser loads a web page, it 
creates a model of the page in memory. 
The DOM specifies the way in which the 
browser should structure this model using 
a DOM tree. 
The DOM is called an object model 
because the model (the DOM tree) is 
made of objects. 
Each object represents a different part of 
the page loaded in the browser window.   

2. ACCESSING AND CHANGING 
THE HTML PAGE 
The DOM also defines methods and 
properties to access and update each 
object in this model, which in turn updates 
what the user sees in the browser. 
You will hear people call the DOM an 
Application Programming Interface (API). 
User interfaces let humans interact with 
programs; APls let programs (and scripts) 
talk to each other. The DOM states what 
your script can "ask the browser about the 
current page, and how to tell the browser 
to update what is being shown to the user. 

* THE DOM TREE IS A MODEL OF A WEB PAGE  

As a browser loads a web page, it creates a model of that page. 
The model is called a DOM tree, and it is stored in the browsers' memory. 
It consists of four main types of nodes. 

1. THE DOCUMENT NODE 
2. ELEMENT NODES 
3. ATTRIBUTE NODES 
4. TEXT NODES 

* WORKING WITH THE DOM TREE   
 Accessing and updating the DOM tree involves two steps:   
 1. Locate the node that represents the element you want to work with. 
 2. Use its text content, child elements, and attributes. 


