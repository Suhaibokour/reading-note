# HTML Lists, Control Flow with JS, and the CSS Box Model

## LISTS
1. Numbered lists
2. Bullet lists
3. Definition lists

### There are lots of occasions when we need to use lists. HTML provides us with three different types

* Ordered lists are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number

* ● Unordered lists are lists that begin with a bullet point 
(rather than characters that indicate order)

* Definition lists are made up of a set of terms along with the 
definitions for each of those terms

---

## BOXES

### Box Dimensions (width, height)

By default a box is sized just big 
enough to hold its contents. To 
set your own dimensions for a 
box you can use the height and 
width properties.The most popular ways to 
specify the size of a box are 
to use pixels, percentages, or 
ems. Traditionally, pixels have 
been the most popular method 
because they allow designers to 
accurately control their size.

### Limiting Width (min-width, max-width)

Some page designs expand and 
shrink to fit the size of the user's 
screen. In such designs, the 
min-width property specifies 
the smallest size a box can be 
displayed at when the browser 
window is narrow, and the 
max-width property indicates 
the maximum width a box can 
stretch to when the browser 
window is wide. These are very helpful properties 
to ensure that the content of 
pages are legible (especially on 
the smaller screens of handheld 
devices). For example, you can 
use the max-width property to 
ensure that lines of text do not 
appear too wide within a big 
browser window and you can 
use the min-width property 
to make sure that they do not 
appear too narrow.  

### Limiting Height(min-height, max-height)

In the same way that you might 
want to limit the width of a box 
on a page, you may also want 
to limit the height of it. This is 
achieved using the min-height
and max-height properties.

### Overflowing Content

* overflow   
The overflow property tells the 
browser what to do if the content 
contained within a box is larger 
than the box itself. It can have 
one of two values.  

* hidden  
This property simply hides any 
extra content that does not fit in 
the box.  

* scroll  
This property adds a scrollbar to 
the box so that users can scroll 
to see the missing content.

#### Every box has three available properties that can be adjusted to control its appearance

1. Border  
Every box has a border (even if 
it is not visible or is specified to 
be 0 pixels wide). The border 
separates the edge of one box 
from another.

2. Margin  
Margins sit outside the edge 
of the border. You can set the 
width of a margin to create a 
gap between the borders of two 
adjacent boxes.  
3. Padding  
Padding is the space between 
the border of a box and any 
content contained within it. 
Adding padding can increase the 
readability of its contents.

---

### SWITCH STATEMENTS 

A switch statement starts with a 
variable called the switch value. 
Each case indicates a possible 
value for this variable and the 
code that should run if the 
variable matches that value. 

#### TYPE COERCION & WEAK TYPING  
* JavaScript can convert data 
types behind the scenes to 
complete an operation. This is 
known as type coercion. For 
example, a string 'l ' could be 
converted to a number 1 in the 
following expression:(' 1' > 0). 
As a result, the above expression 
would evaluate to true. 
* JavaScript is said to use weak 
typing because the data type 
for a value can change. Some 
other languages require that you 
specify what data type 
each variable will be. They are 
said to use strong typing.