# Object-Oriented Programming, HTML Tables
--- 

### Tables
There are several types of information 
that need to be displayed in a grid or 
table. For example: sports results, stock 
reports, train timetables.
When representing information in a table, you need to think 
in terms of a grid made up of rows and columns (a bit like a 
spreadsheet).

#### so what is a table?  
A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results. Grids allow us to understand 
complex data by referencing 
information on two axes. Each block in the grid is referred 
to as a table cell. In HTML a 
table is written out row by row.  

* Basic Table Structure  
``` 
<table>
 <tr>
 <td>15</td>
 <td>15</td>
 <td>30</td>
 </tr>
 <tr>
 <td>45</td>
 <td>60</td>
 <td>45</td>
 </tr>
 <tr>
 <td>60</td>
 <td>90</td>
 <td>90</td>
 </tr>
</table>
```
---
### Object-Oriented Programming


*  CREATE THE OBJECT, THEN ADD PROPERTIES & METHODS   

In both of these examples, the object is created on 
the first line of the code sample. The properties and 
methods are then added to it afterwards.
1. LITERAL NOTATION 
```
var hotel = {} 
hotel .name= 'Quay'; 
hotel .rooms = 40; 
hotel.booked = 25; 
hotel.checkAvailabil ity =function() {
return this.rooms - this .booked; 
} ; 
```

Once you have created an object, the syntax for 
adding or removing any properties and methods 
from that object is the same.

2. OBJECT CONSTRUCTOR NOTATION 
```
var hotel = new Object(); 
hotel.name = 'Quay'; 
hotel .rooms = 40; 
hotel . booked= 25; 
hotel.checkAvailability =function(){
return this .rooms - this.booked; 
} ;
```
* (THIS) keyword.  
The keyword this is commonly used inside functions and objects. 
Where the function is declared alters what this means. It always refers 
to one object, usually the object in which the function operates.

* STORING DATA  
In JavaScript, data is represented using name/value pairs. 
To organize your data, you can use an array or object to group a set of 
related values. In arrays and objects the name is also known as a key. If you want to access items via a property name or key, use an object 
(but note that each key in the object must be unique). 
If the order of the items is important, use an array. 