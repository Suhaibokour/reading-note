# HTML Links, JS Functions, and Intro to CSS Layout
---

### links   
Links are the defining feature of the web 
because they allow you to move from 
one web page to another — enabling the 
very idea of browsing or surfing.



* Links are created using the \<a> element
* The \<a> element uses the href attribute to indicate 
the page you are linking to
*  If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs
*  You can create links to open email programs with an 
email address in the "to" field
* You can use the id attribute to target elements within 
a page that can be linked to

#### Linking to Other Pages on the Same Site
```<p>
<ul>
 <li><a href="index.html">Home</a></li>
 <li><a href="about-us.html">About</a></li>
 <li><a href="movies.html">Movies</a></li>
 <li><a href="contact.html">Contact</a></li>
</ul>
</p>
 ```  

 #### Linking to Other Sites   

 ``` 
 <p>Movie Reviews:
<ul>
 <li><a href="http://www.empireonline.com">
 Empire</a></li>
 <li><a href="http://www.metacritic.com">
 Metacritic</a></li>
 <li><a href="http://www.rottentomatoes.com">
 Rotten Tomatoes</a></li>
 <li><a href="http://www.variety.com">
 Variety</a></li>
</ul>
</p> 
```  

#### Email Links _mailto:_

```
<a href="mailto:jon@example.org">Email Jon</a>
``` 

#### Opening Links ina New Window  
``` 
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> 
``` 
 ### Layout

 * Normal Flow (position:static)

 n normal flow, each block-level 
element sits on top of the next 
one. Since this is the default 
way in which browsers treat 
HTML elements, you do not 
need a CSS property to indicate 
that elements should appear 
in normal flow


 * Relative Positioning position:relative  
 Relative positioning moves an 
element in relation to where it 
would have been in normal flow
 * Absolute Positioning position:absolute  

 When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.)
 * Fixed Positioning position:fixed

 Fixed positioning is a type 
of absolute positioning that 
requires the position property 
to have a value of fixed
 
 ---

 ### FUNCTIONS, METHODS & OBJECTS

 #### WHAT IS A FUNCTION? 
 Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

#### WHAT IS AN OBJECT?

Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

