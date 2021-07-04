# HTML, CSS and JS.

### Markup   

 Markup language is a system for annotating a document in a way that is visually distinguishable from the content. It is used only to format the text, so that when the document is processed for display, the markup language does not appear. 

* Structural markup:  
the elements that you can use to 
describe both headings and paragraphs

* Semantic markup:   which provides extra information; such 
as where emphasis is placed in a sentence, that something 
you have written is a quotation (and who said it), the 
meaning of acronyms, and so on


![md](https://i.insider.com/60197cf301504a00197fb20f)
#### HTML has six "levels" of headings:

\<h1> is used for main headings   

\<h2> is used for subheadings   

If there are further sections 
under the subheadings then the 
\<h3> element is used, and so 
on...   

Browsers display the contents of 
headings at different sizes. The 
contents of an \<h1> element is 
the largest, and the contents of 
an \<h6> element is the smallest. 
The exact size at which each 
browser shows the headings 
can vary slightly. Users can also 
adjust the size of text in their 
browser. You will see how to 
control the size of text, its color, 
and the fonts used when we 
come to look at CSS.   
### Paragraphs 

To create a paragraph, surround 
the words that make up the 
paragraph with an opening \<p>
tag and closing \</p> tag.
By default, a browser will show 
each paragraph on a new line 
with some space between it and 
any subsequent paragraphs.

### ***bold and Italic***

* By enclosing words in the tags 
\<b> and \</b> we can make 
characters appear bold.
The \<b> element also represents 
a section of text that would be 
presented in a visually different 
way (for example key words in a 
paragraph) although the use of 
the \<b> element does not imply 
any additional meaning.  

* By enclosing words in the tags 
\<i> and \</i> we can make 
characters appear italic.
The \<i> element also represents 
a section of text that would be 
said in a different way from 
surrounding content — such as 
technical terms, names of ships, 
foreign words, thoughts, or other 
terms that would usually be 
italicized.

#### Visual Editors & Their Code views

* Visual editors often resemble 
word processors. Although 
each editor will differ slightly, 
there are some features that 
are common to most editors 
that allow you to control the 
presentation of text.
* Code views show you the code 
created by the visual editor so 
you can manually edit it, or so 
you can just enter new code 
yourself. It is often activated 
using a button with an icon 
that says HTML or has angled 
brackets. White space may be 
added to the code by the editor 
to make the code easier to read.

### Strong & Emphasis
* \<strong>
The use of the \<strong>
element indicates that its 
content has strong importance. 
For example, the words 
contained in this element might 
be said with strong emphasis.
By default, browsers will show 
the contents of a \<strong>
element in bold.

* \<em>
The \<em> element indicates 
emphasis that subtly changes 
the meaning of a sentence.
By default browsers will show 
the contents of an \<em> element 
in italic.

### Quotations  
* \<blockquote>
The \<blockquote> element is 
used for longer quotes that take 
up an entire paragraph. Note 
how the \<p> element is still 
used inside the \<blockquote>
element. 
Browsers tend to indent the 
contents of the \<blockquote>
element, however you should not 
use this element just to indent a 
piece of text — rather you should 
achieve this effect using CSS.
* \<q>
The \<q> element is used for 
shorter quotes that sit within 
a paragraph. Browsers are 
supposed to put quotes around 
the \<q> element, however 
Internet Explorer does not — 
therefore many people avoid 
using the \<q> element.
Both elements may use the cite
attribute to indicate where the 
quote is from. Its value should 
be a URL that will have more 
information about the source of 
the quotation.

![html](https://elzero.org/wp-content/uploads/2019/06/learn-html4.png)

#### summary

* HTML elements are used to describe the structure of 
the page (e.g. headings, subheadings, paragraphs).
* They also provide semantic information (e.g. where 
emphasis should be placed, the definition of any 
acronyms used, when given text is a quotation).

---

### CSS
* CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.  

* CSS works by associating rules with HTML elements. These rules govern 
how the content of specified elements should be displayed. A CSS rule 
contains two parts: a selector and a declaration     

* CSS declarations sit inside curly brackets and each is made up of two 
parts: a property and a value, separated by a colon. You can specify 
several properties in one declaration, each separated by a semi-colon

![css](https://e3arabi.com/wp-content/uploads/2021/02/css-framework-780x470.jpg)

### javaScript
* STATEMENTS   
A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon. 

* COMMENTS  
You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code.  

* VARIABLES

A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables.

* DATA TYPES
- NUMERIC DATA TYPE 
The numeric data type handles 
numbers. 
- STRING DATA TYPE 
The strings data type consists of 
letters and other characters.
- true  
It might seem a little abstract at 
first, but the Boolean data type is 
actually very helpful. 

![javascript](https://3.bp.blogspot.com/-tfdMQH1Kszg/XD-diQnmSuI/AAAAAAAAMCg/ZQyeDQIaxrQYMJX_bqExOGOKtQQJ3M0wgCLcBGAs/s1600/%25D9%2584%25D8%25BA%25D8%25A9%2B%25D8%25AC%25D8%25A7%25D9%2581%25D8%25A7%2B%25D8%25B3%25D9%2583%25D8%25B1%25D9%258A%25D8%25A8%25D8%25AA%2BJavaScript.png)


##### **RULES FOR NAMING VARIABLES** 
1. It might seem a little abstract at 
first, but the Boolean data type is 
actually very helpful. 
2. The name can contain letters, 
numbers, dollar sign ($), or an 
underscore (_). Note that you 
must not use a dash(-) or a 
period (.) in a variable name.
3. You cannot use keywords or 
reserved words. Keywords 
are special words that tell the 
interpreter to do something. For 
example, var is a keyword used 
to declare a variable. Reserved 
words are ones that may be used 
in a future version of JavaScript. 
ONLINE EXTRA 
View a full list of keywords and 
reserved words in JavaScript.
4. All variables are case sensitive, 
so score and Score would be 
different variable names, but 
it is bad practice to create two 
variables that have the same 
name using different cases.
5. Use a name that describes the 
kind of information that the 
variable stores. For example, 
fi rstName might be used to 
store a person's first name, 
l astNarne for their last name, 
and age for their age.
6. If your variable name is made 
up of more than one word, use a 
capital letter for the first letter of 
every word after the first word. 
For example, f i rstName rather 
than fi rstnarne (this is referred 
to as camel case). You can also 
use an underscore between each 
word (you cannot use a dash).




