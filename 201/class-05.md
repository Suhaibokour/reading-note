# HTML Images; CSS Color & Text

### Imges
A picture can say a thousand words, and great 
images help make the difference between an 
average-looking site and a really engaging one


* Adding Images  

``` <img src="images/quokka.jpg" alt="A family of 
 quokka" title="The quokka is an Australian 
 marsupial that is similar in size to the 
 domestic cat." />
 ```
* Height & Width of Images  
``` 
<img src="images/quokka.jpg" alt="A family of 
 quokka" width="600" height="450" />
 ``` 
* Aligning Images Horizontally  
``` 
<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" align="left" />There are around 
 10,000 living species of birds that inhabit 
 different ecosystems from the Arctic to the 
 Antarctic. Many species undertake long distance 
 annual migrations, and many more perform shorter 
 irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" align="right" />There are around 
 10,000 living species of birds that inhabit 
 different ecosystems from the Arctic to the 
 Antarctic. Many species undertake long distance 
 annual migrations, and many more perform shorter 
 irregular journeys.</p>
 ```
 * Aligning Images Vertically  
 ``` 
 <p><img src="images/bird.gif" alt="Bird" width="100" 
 height="100" align="top" />There are around 
10,000 living species of birds that inhabit 
different ecosystems from the Arctic to the 
Antarctic. Many species undertake long distance 
annual migrations, and many more perform shorter 
irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" 
 height="100" align="middle" />There are around 
10,000 living species of birds that inhabit 
different ecosystems from the Arctic to the 
Antarctic. Many species undertake long distance 
annual migrations, and many more perform shorter 
irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" 
 height="100" align="bottom" />There are around 
10,000 living species of birds that inhabit 
different ecosystems from the Arctic to the 
Antarctic. Many species undertake long distance 
annual migrations, and many more perform shorter 
irregular journeys.</p>
```
* Three Rules for Creating Images  
1. Save images in 
the right format
Websites mainly use images in 
jpeg, gif, or png format. If you 
choose the wrong image 
format then your image might 
not look as sharp as it should 
and can make the web page 
slower to load. 
2. Save images at 
the right size
You should save the image at 
the same width and height it will 
appear on the website. If 
the image is smaller than the 
width or height that you have 
specified, the image can be 
distorted and stretched. If the 
image is larger than the width 
and height if you have specified, 
the image will take longer to 
display on the page.
3. Use the correct
resolution
Computer screens are made up 
of dots known as pixels. Images 
used on the web are also made 
up of tiny dots. Resolution refers 
to the number of dots per inch, 
and most computer screens only 
show web pages at 72 pixels 
per inch. So saving images at 
a higher resolution results in 
images that are larger than 
necessary and take longer to 
download.

---

### colors 


* color proparety  

The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:
1. rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)
2. hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80
3. color names
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan

* Background Color  
CSS treats each HTML element 
as if it appears in a box, and the 
background-color property 
sets the color of the background 
for that box.
You can specify your choice of 
background color in the same 
three ways you can specify 
foreground colors: RGB values, 
hex codes, and color names 

1. RGB Values  
Values for red, green, and blue 
are expressed as numbers 
between 0 and 255. 
(rgb(102,205,170))

2. Hex Codes  
Hex values represent values 
for red, green, and blue in 
hexadecimal code.
(#66cdaa)
3. Color Names  
Colors are represented by 
predefined names. However, 
they are very limited in number.
(MediumAquaMarine)
4. Hue  
Hue is near to the colloquial idea 
of color. Technically speaking 
however, a color can also have 
saturation and brightness as 
well as hue.
5. Saturation  
Saturation refers to the amount 
of gray in a color. At maximum 
saturation, there would be no 
gray in the color. At minimum 
saturation, the color would be 
mostly gray
6. Brightness  
Brightness (or "value") refers 
to how much black is in a color. 
At maximum brightness, there 
would be no black in the color. 
At minimum brightness, the 
color would be very dark.

* CSS3: Opacity opacity, rgba 

CSS3 introduces the opacity
property which allows you to 
specify the opacity of an element 
and any of its child elements. 
The value is a number between 
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% 
opacity)

``` 
p.one {
background-color: rgb(0,0,0);
opacity: 0.5;}
p.two {
background-color: rgb(0,0,0);
background-color: rgba(0,0,0,0.5);}
``` 
* hsl, hsla  

The hsl color property has 
been introduced in CSS3 as an 
alternative way to specify colors. 
The value of the property starts 
with the letters hsl, followed 
by individual values inside 
parentheses for

1. hue
This is expressed as an angle 
(between 0 and 360 degrees).
2. saturation
This is expressed as a 
percentage
3. lightness
This is expressed as a 
percentage with 0% being white, 
50% being normal, and 100% 
being black. 
``` 
body {
background-color: #C8C8C8;
background-color: hsl(0,0%,78%);}
p {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);}
``` 
---
### Text 
The properties that allow you to control 
the appearance of text can be split into 
two groups:
1. Those that directly affect the font and its appearance 
(including the typeface, whether it is regular, bold or italic, 
and the size of the text)
2. Those that would have the same effect on text no matter 
what font you were using (including the color of text and 
the spacing between words and letters)

