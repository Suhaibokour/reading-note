# CSS Layout

* Building Blocks  

CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks 
of any layout, while inline boxes flow between surrounding text. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors. 

* Containing Elements  

If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.
It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together 
all of the elements that form the header of a site (such as the logo and 
the main navigation). The <div> element that contains this group of 
elements is then referred to as the containing element. 

---

* Controlling the Position of Elements 

CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property. 

1. Normal flow  

Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else).

2. Relative Positioning  

This moves an element from the 
position it would be in normal 
flow, shifting it to the top, right, 
bottom, or left of where it 
would have been placed. This 
does not affect the position of 
surrounding elements; they stay 
in the position they would be in 
in normal flow.

3. Absolute positioning  

This positions the element 
in relation to its containing 
element. It is taken out of 
normal flow, meaning that it 
does not affect the position 
of any surrounding elements 
(as they simply ignore the 
space it would have taken up). 
Absolutely positioned elements 
move as users scroll up and 
down the page.  

4. Fixed Positioning  

This is a form of absolute 
positioning that positions 
the element in relation to the 
browser window, as opposed 
to the containing element. 
Elements with fixed positioning 
do not affect the position of 
surrounding elements and they 
do not move when the user 
scrolls up or down the page.

5. Floating Elements  

Floating an element allows 
you to take that element out 
of normal flow and position 
it to the far left or right of a 
containing box. The floated 
element becomes a block-level 
element around which other 
content can flow. 

---


* Normal Flow (position:static)  


In normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow, but the syntax 
would be:
position: static; 
I have not specified a width
property for the heading 
element, so you can see how it 
stretches the width of the entire 
browser window by default.
The paragraphs are restricted 
to 450 pixels wide. This shows 
how the elements in normal flow 
start on a new line even if they 
do not take up the full width of 
the browser window.   

* Relative Positioning (position:relative)  
Relative positioning moves an 
element in relation to where it 
would have been in normal flow.
For example, you can move it 10 
pixels lower than it would have 
been in normal flow or 20% to 
the right.
You can indicate that an element 
should be relatively positioned 
using the position property 
with a value of relative.
You then use the offset 
properties (top or bottom and 
left or right) to indicate how 
far to move the element from 
where it would have been in 
normal flow.
To move the box up or down, 
you can use either the top or 
bottom properties.
To move the box horizontally, 
you can use either the left or 
right properties.
The values of the box offset 
properties are usually given in 
pixels, percentages or ems.    

* Absolute Positioning (position:absolute)  

When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.) 
The box offset properties (top
or bottom and left or right) 
specify where the element 
should appear in relation to its 
containing element.
In this example, the heading has 
been positioned at the top of the 
page and 500 pixels from its left 
edge. The width of the heading is 
set to be 250 pixels wide.
The width property has 
also been applied to the \<p>
elements in this example 
to prevent the text from 
overlapping and becoming 
unreadable.

* Fixed Positioning (position:fixed)  


Fixed positioning is a type 
of absolute positioning that 
requires the position property 
to have a value of fixed.
It positions the element in 
relation to the browser window. 
Therefore, when a user scrolls 
down the page, it stays in the 
exact same place. It is a good 
idea to try this example in your 
browser to see the effect.
To control where the fixed 
position box appears in relation 
to the browser window, the box 
offset properties are used.
In this example, the heading 
has been positioned to the top 
left hand corner of the browser 
window. When the user scrolls 
down the page, the paragraphs 
disappear behind the heading.
The \<p> elements are in normal 
flow and ignore the space that 
the \<h1> element would have 
taken up. Therefore, the 
margin-top property has 
been used to push the first \<p>
element below where the fixed 
position \<h1> element is sitting.

* Overlapping Elements (z-index)  


When you use relative, fixed, or 
absolute positioning, boxes can 
overlap. If boxes do overlap, the 
elements that appear later in the 
HTML code sit on top of those 
that are earlier in the page. 
If you want to control which 
element sits on top, you can use 
the z-index property. Its value 
is a number, and the higher the 
number the closer that element 
is to the front. For example, an 
element with a z-index of 10
will appear over the top of one 
with a z-index of 5.
This example looks similar to 
the one on page 368, but it 
uses relative positioning for 
the \<p> elements. Because 
the paragraphs are relatively 
positioned, by default they 
would appear over the top of the 
heading as the user scrolls down 
the page. To ensure that the 
\<h1> element stays on top, we 
use the z-index property on the 
rule for the \<h1> element.
The z-index is sometimes 
referred to as the stacking 
context (as if the blocks have 
been stacked on top of each 
other on a z axis). If you are 
familiar with desktop publishing 
packages, it is the equivalent 
of using the 'bring to front' and 
'send to back' features.  

* Floating Elements (float)  

The float property allows you 
to take an element in normal 
flow and place it as far to the 
left or right of the containing 
element as possible.
Anything else that sits inside 
the containing element will 
flow around the element that is 
floated.
When you use the float
property, you should also use the 
width property to indicate how 
wide the floated element should 
be. If you do not, results can be 
inconsistent but the box is likely 
to take up the full width of the 
containing element (just like it 
would in normal flow).
In this example, a 
\<blockquote> element is 
used to hold a quotation. It's 
containing element is the 
\<body> element.
The \<blockquote> element 
is floated to the right, and the 
paragraphs that follow the quote 
flow around the floated element.

* Using Float to Place  Elements Side-by-Side  


A lot of layouts place boxes 
next to each other. The float
property is commonly used to 
achieve this.
When elements are floated, the 
height of the boxes can affect 
where the following elements sit.
In this example, you can see six 
paragraphs, each of which has a 
width and a float property set.
The fourth paragraph does not 
go across to the left hand edge 
of the page as one might expect. 
Rather it sits right under the 
third paragraph.
The reason for this is that the 
fourth paragraph has space to 
start under the third paragraph, 
but it cannot go any further to 
the left because the second 
paragraph is in the way.
Setting the height of the 
paragraphs to be the same 
height as the tallest paragraph 
would solve this issue, but it 
is rarely suited to real world 
designs where the amount of 
text in a paragraph or column 
may vary. It is more common 
to use the clear property 
(discussed on the next page) to 
solve this issue.  

* Clearing Floats (clear)    

The clear property allows you 
to say that no element (within 
the same containing element) 
should touch the left or righthand sides of a box. It can take 
the following values:
left
The left-hand side of the box 
should not touch any other 
elements appearing in the same 
containing element.
right
The right-hand side of the 
box will not touch elements 
appearing in the same containing 
element.
both
Neither the left nor right-hand 
sides of the box will touch 
elements appearing in the same 
containing element.
none
Elements can touch either side.
In this example, the fourth 
paragraph has a class called 
clear. The CSS rule for this 
class uses the clear property 
to indicate that nothing should 
touch the left-hand side of it. The 
fourth paragraph is therefore 
moved further down the page 
so no other element touches its 
left-hand side.  

* Parents of Floated Elements: Problem  


 If a containing element only
contains floated elements, some 
browsers will treat it as if it is 
zero pixels tall.
As you can see in this example, 
the one pixel border assigned 
to the containing element has 
collapsed, so the box looks like a 
two pixel line.  

* Parents of Floated Elements: Solution  

Traditionally, developers got 
around this problem by adding 
an extra element after the 
last floated box (inside the 
containing element). A CSS 
rule would be applied to this 
additional element setting the 
clear property to have a value 
of both. But this meant that an 
extra element was added to the 
HTML just to fix the height of the 
containing element.
More recently, developers have 
opted for a purely CSS-based 
solution because it means that 
there is no need to add an extra 
element to the HTML page after 
the floated elements. The pure 
CSS solution adds two CSS rules 
to the containing element (in this 
example the \<div> element):
● The overflow property is 
given a value auto.
● The width property is set to 
100%.  

* Creating Multi-Column Layouts with Floats  

Many web pages use multiple 
columns in their design. This 
is achieved by using a \<div>
element to represent each 
column. The following three CSS 
properties are used to position 
the columns next to each other: 
width
This sets the width of the 
columns.
float
This positions the columns next 
to each other.
margin
This creates a gap between the 
columns.
A two-column layout like the one 
shown on this page would need 
two \<div> elements, one for the 
main content of the page and 
one for the sidebar.
Inside each of the \<div>
elements there can be headings, 
paragraphs, images, and even 
other \<div> elements.  



































