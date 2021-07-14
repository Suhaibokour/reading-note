# Forms and JS Events
---
### forms
Traditionally, the term 'form' has referred 
to a printed document that contains 
spaces for you to fill in information.  

* why form?

In addition to enabling users to 
search, forms also allow users 
to perform other functions 
online. You will see forms 
when registering as a member 
of a website, when shopping 
online, and when signing up for 
newsletters or mailing lists.  

* form controls  
1. ADDING TEXT:
2. Making Choices:
3. Submitting Forms:
4. Uploading Files:

* how forms work?
1. A user fills in a form and then presses a button 
to submit the information to the server.
2. The name of each form 
control is sent to the 
server along with the 
value the user enters or 
selects.
3. The server processes 
the information using a 
programming language 
such as PHP, C#, VB.net, 
or Java. It may also store 
the information in a 
database
4. The server creates a new 
page to send back to the 
browser based on the 
information received.


---

### Lists, Tables and Forms  

* Bullet Point Styles  
The list-style-type property 
allows you to control the shape 
or style of a bullet point (also 
known as a marker). 
It can be used on rules that 
apply to the \<ol>, \<ul>, and \<li>
elements

* Images for Bullets  
You can specify an image to act 
as a bullet point using the
list-style-image property.
The value starts with the letters 
url and is followed by a pair 
of parentheses. Inside the 
parentheses, the path to the 
image is given inside double 
quotes.
This property can be used on 
rules that apply to the <ul> and 
<li> elements.
The example on this page also 
shows the use of the margin
property to increase the vertical 
gap between each item in the 
list  
* Positioning the Marker  
Lists are indented into the page 
by default and the list-styleposition property indicates 
whether the marker should 
appear on the inside or the 
outside of the box containing the 
main points. 
This property can take one of 
two values:
outside
The marker sits to the left of the 
block of text. (This is the default 
behaviour if this property is not 
used.)
inside
The marker sits inside the box of 
text (which is indented).
In the example shown, the width 
of the list has been limited to 150 
pixels. This ensures that the text 
wraps onto a new line so you can 
see how the value of inside sits 
the bullet inside the first line of 
text. 
A margin has been added to 
each list item so that there is a 
clear gap between each.

* List Shorthand 
As with several of the other CSS 
properties, there is a property 
that acts as a shorthand for list 
styles. It is called list-style, 
and it allows you to express 
the markers' style, image and 
position properties in any order

---

### events

W hen you browse the web, your browser registers different 
types of events. It's the browser's way of saying, "Hey, this 
just happened." Your script can then respond to these events. 

* HOW EVENTS TRIGGER JAVASCRIPT CODE  

When the user interacts with the HTML on a web page, there are three 
steps involved in getting it to trigger some JavaScript code. 
Together these steps are known as event handling. 
1. Select t he element 
node(s) you want the 
script to respond to. 
For example, if you want to 
trigger a function when a user 
clicks on a specific link, you need 
to get the DOM node for that 
link element.
2. Indicate which event on 
the selected node(s) will 
trigger the response. 
Programmers call this binding an 
event to a DOM node. 
The previous two pages showed 
a selection of the popular events 
that you can monitor for.
3. State the code you want 
to run when the event 
occurs. 
W hen the event occurs, on a 
specified element, it will trigger 
a function. This may be a named 
or an anonymous function. 



