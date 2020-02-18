## Code 201 Reading Notes

This is a place for me to organize my thoughts and take notes on [Web Design with HTML, CSS, JavaScript and JQuery](https://www.amazon.com/Web-Design-HTML-JavaScript-jQuery/dp/1118907442) assigned readings in Code 201. Feel free to learn along with me.

### Table of Contents
- [Read: 01](#first-daily-reading)
- [Read: 02](#second-daily-reading)
- [Read: 03](#third-daily-reading)
- [Read: 04](#fourth-daily-reading)
- [Read: 05](#fifth-daily-reading)
- [Read: 06](#sixth-daily-reading)
- [Read: 07](#seventh-daily-reading)
- [Read: 08](#eighth-daily-reading)
- [Read: 09](#ninth-daily-reading)
- [Read: 10](#tenth-daily-reading)
- [Read: 11](#eleventh-daily-reading)
- [Read: 12](#twelfth-daily-reading)
- [Read: 13](#thirteenth-daily-reading)
- [Read: 14](#fourteenth-daily-reading)
- [Read: 15](#fifteenth-daily-reading)



#### First Daily Reading

```
HTML Chapter 1: Structure
<html>
  <body>
    <h1>
      <p></p>
    <h2>
      <p></p>
  </body>
</html>

opening tags | closing tags

attributes
  - attribute name
  - attribute value

- <body>
- <head>
- <title>
```
```
HTML Chapter 8: Extra Markup

- <!DOCTYPE html>
- <!-- -->

id and class attribute

block elements

inline elements

- <div>
- <span>
- <iframe>
- <meta>

escape characters
```
```
HTML Chapter 17: HTML5 Layout

- <header>
- <footer>
- <nav>
- <article>
- <aside>
- <section>
- <hgroup>
- <figure>
- <figcaption>
- <a>
```
```
HTML Chapter 18: Process and Design

Target audience

Who What Where When Why How 

Site maps
  - wireframes
  - design
  - visual heirarchy
  - grouping
  - navigation

code management system  <-- wrong chapter?
```
```
JS Chapter 1: The ABC's of Programming

- A: What is a script and how do I create one?
- B: How do computers fit in the world around them?
- C: How do I write a script for a web page?
```

#### Second Daily Reading

```
HTML Chapter 2: Text
- Headings
  - <h1>...<h6>

- Paragraphs
  - <p></p>

- Text
  - <b>
  - <i>
  - <sup>
  - <sub>
  - <br />
  - <hr /> horizontal rule. basically a line
  - <strong>
  - <em>
  - <blockquote>
  - <q> quote
  - <abbr>
  - <cite>
  - <dfn>
  - <address> physical, email, or phone number
  - <ins> inserted text (underlined)
  - <del> deleted text (strikethrough)
  - <s> something no longer accurate or relevant (strikethrough)
  ```
  ```
HTML Chapter 10: CSS
  
  selector      p
  declaration   font-family: Arial;
  property      font-family
  value         Arial

  
  p {
    font-family: Arial;
  }

External CSS
  - <link>
      href
      type
      rel

Internal CSS
  - <style>

Inheritance
  - applies to child elements
```
```
JS Chapter 2: Basic Javascript Instructions

syntax grammar and instructions

statement
  - ends with ;

comments
  - /* */
  - //

variables 
  - variable keyword var
  - variable name
  - assign with = 

data types

operators
```
```
JS Chapter 4: Decisions and Loops

if, else if, else

== != === !==

> < >= <=

logical operators
  - &&
  - ||
  - !

switch statements

booleans

for loops

while loops

do while loops
```


#### Third Daily Reading

HTML Chapter 3: Lists

```
Ordered list
  - <ol>
      <li> </li>
    </ol>

Unordered list
  - <ul>
      <li> </li>
    </ul>

defintion list
  - <dl>
      <dt></dt>
      <dd></dd>
    </dl>

Lists can be nested, eg a <ul> inside an <li>

```
```
HTML Chapter 13: Boxes

Box model
  - margin
  - border
  - padding
  - content

- pixels, ems,

order:
- top, right, bottom, left
- right, left
- all 

borders have many types of stylings available
```
```
JavaScript Chapter 4: Switch statements onward

switch (switch value) {
  case 'option1':
    something happens
  case 'option2':
    something happens
  default;
    something else happens (Default)
}

Truthy and Falsy 

if else statements

For While Do While loops

For (var i = 0; i < 10; i++) {
  code to execute during loop
}

initialization condition update

do while loops
do {
_
_
_
} 
while _______
```


#### Fourth Daily Reading

```
HTML Chapter 4: Links

<a> tag with href=" " > text to click on  </a>

target.html for relative links

child/target.html for links in child directory

../ for parent directory

 

HTML Chapter 15: Layout

Grid model

Inline elements vs Box elements

CSS Frameworks

 

JS Chapter 4: Functions (start)

function keyword

functionname() {

code to run
}
```

#### Fifth Daily Reading
```
HTML Chapter 5: Images

- image elements are an empty element with no closing tag

- <img src="pathway/image.jpg" alt="description of image." />

- use empty "" for alt attribute if image decorative with no meaning

- title element is text that will be displayed if hovered

- width="x" and height="y" specifies image dimensions. If you only define one the browser will auto the other to maintain ratio

- image tags can be placed before <p> (outside it), inside <p> before text, inside <p> after some text.

- if <img> is followed by block level element, then block level element will sit on new line

- use CSS to control alignment of images

- align attributes in HTML is not used anymore 

- 3 rules for images:

     1. save images in right format. jpg(jpeg), gif, or png 

     2. save images at right size. if <img> specifies differently image will be distorted

     3. use correct resolution. most computer screens are 72 pixels per inch

- vector images are different from bitmap images and are resolution independent. .svg files.

- animated gifs are a thing

-transparency: if the transparent part of image has straight edges and is 100% transparent you can use a gif. else use png

- <figure> 

    <img>

    <figcaption> caption </figcaption>

    </figure>

 

HTML Chapter 11: Color

- CSS color can be defined in 3 ways. 1) RGB values eg. rgb(100,100,90) 2) hex codes eg. #ee3e80 3) color names, there are 147 predefined color names

- background-color: white;

- make sure text has enough contrast to be readable 

- opacity property in CSS

- opacity: 0.5;

- hsla = hue, saturation, lightness, alpha

- background-color: #ffffff;

   background-color: hsla(0,100%,100%,0.5);

- alpha means transparency 

 

HTML Chapter 12: Text

- CSS text properties fall into two groups: 1) directly affect font and appearance, like typeface, bold, size 2) affect text no matter what font you're using, like color of text and spacing between words and letter

- serif fonts: extra details (lines) at ends of main strokes of letters

- sans-serif: straight ends without lines

- monospace: fixed width

- weight: light medium bold black

- style: normal italic oblique

- stretch: condensed regular extended

- if choose a typeface browser will only display it if it's installed on user's computer

- it's possible to specify more than one typeface and order of preference 

- font-family: Georgia, Times, serif;

- font-family: "Courier New", Courier, monspace;  <--- use double quotes if font name has more than one word

- design tip, use no more than 3 types of fonts per page

- font-size: 12px;

200%;   <--- of default

1.3em; <--- equivalent to the width of a letter m

- relative proportions of size of text

- default size of text in web browser is 16 pixels

- @font-face {

          font-family: 'ChunkFiveRegular';

          src: url('fonts/chunkfive.eot'); }

h1, h2 {

          font-family: ChunkFiveRegular, Georgia, serif;}

- @font-face allows you to use a font even if not installed on computer

define many src url's to ensure browser coverage

font formats should appear in this order: eot woff tff/otf svg

- font-weight: bold;

- font-style: normal;

italic;

oblique;

- text-transform: uppercase;

lowercase;

capitalize;

- text-decoration: none;

underline;

overline;

line-through;

blink;

- leading is vertical space between lines of text

- line-height: 1.4em;

line-height is font-size + leading

best to give in ems

- kerning is space between each letter

letter-spacing: 0.2em;

- gap between words:

word-spacing: 1em;

- use ems for letter-spacing and word-spacing

- default spacing around 0.25em

- text-align: left;

justify;

right;

center;

- vertical-align property does not let you vertically align text in the middle of block level elements like <p> and <div>, though it does work for <td> and <th>

- it's used with inline elements like <img> <em> or <strong>. similar task to HTML align attribute

- vertical-align: baseline;

sub;

super;

top;

text-top;

middle;

bottom;

text-bottom;

-it can also take length in pixels or ems or percentage of line height

- text-indent: 20px;

- indents first line of text within an element

- negative indent can take text off screen

-text-shadow: (how far left or right) (distance to top or bottom) (optional; blur) (color)

- text-shadow: 2px 2px 7px #111111;

- you can specify different values for first letter or first line of text inside an element with:

:first-letter

:first-line

- not properties but pseudo-elements at end of the selector

p.intro:first-letter {

     font-size: 200%;}

- pseudo-class acts like an extra value for a class attribute

other pseudo-classes:

:link

:visited

:hover

:active

:focus

 

More CSS selectors:

existence [] p[class] - target any <p> element with an attribute called class

equality [=] p[class="dog] targets any <p> element with an attribute called class whose value is dog

space [~=] matches specific attribute whose value is in a space separated list of words

prefix [^=] value begins with a specific string p[attr^"d"]

substring [*=] attribute whose value contains a specific substring p[attr*"do"]

suffix [$=] ends with a specific string p[attr$"g"]
```

#### Sixth Daily Reading
 ```
 ***just use jQuery

JS Chapter 3: Object Literals 

Object variables are known as properties

Object functions are known as methods

Properties and methods have keys and values

var objectName = {

key: value,

methodName: function () {

}

};

objects can be created through literal notation like above^

Dot notation can access properties or methods:

var newVar = objectName.propertyName;

var newVar = objectName.methodName();

Square bracket syntax can access properties but not methods:

var newVar = objectName['propertyName'];

 

JS Chapter 5: Document Object Model DOM

The DOM allows JS to manipulate HTML

DOM allows browser to create a model of HTML page and how JS access/updates content. It's a separate set of rules. The model (the DOM tree) is made of objects. 

API application program interface let programs and scripts talk to each other.

DOM Tree:

- Document Node

- Element Node

- Attribute Node

- Text Node

Access & Update DOM tree:

1. locate node for element you want to work with

2. use its text/child elements/attributes

Elements & element nodes are used interchangeably

Methods that find elements in DOM tree are called DOM queries 

To store element in a variable you store the DOM tree location of the element in a variable. Also known as caching the selection. Variable stores a reference to object in DOM tree.

var newVar = elementMethod('parameter');

^this stores a reference to the element, not the (potential) text content of element. To do so use dot notation. 

DOM queries can return one element, or a NodeList which is a collection of nodes. If a method CAN return more than one node, it will ALWAYS return a NodeList. You can select element you want from this list with index number, using item(#) method or array[#]. 

Methods That Return Single Element Node:

getElementById('id')

querySelector('css selector')

NodeList:

getElementsByClassName('class')

getElementsByTagName('tagName')

querySelectorAll('css selector')

You can loop through NodeList to apply code through numerous elements

Traversing the DOM: When you have an element node, you can select another element by its relation using 5 properties:

1. parentNode

2. previousSibling

3. nextSibling

4. firstChild

5. lastChild

Accessing and changing a text node,

1. access element node

2. access text node

3. text node has property nodeValue which returns the text in that text node

or use nodeValue to update content of a text node

or use textContent property

Avoid innerText property 

You can add or remove HTML content with innerHTML property (there are risks, don't use it) or DOM manipulation

- itemContent update text and markup

Add elements with DOM manipulation

1. createElement()

2. createTextNode()

3. appendChild()

removeChild() method to remove element

Defend against XSS attacks
```

#### Seventh Daily Reading
```
Domain Modeling:

- A model describes various entities, their attributes and behavior, and constraints, that all govern the problem domain. The problem domain is like a big umbrella that models abstract objects. Objects have attributes and behavior

- Constructor functions build self contained objects with the same attributes and behavior (but not necessarily the same values)

- Constructor is defined using a function expression

- After constructor function is define, instantiate with the new keyword and initialize by calling the function()

 

HTML Chapter 6: Tables

Tables can be thought of a grid of rows and columns, kind of like a spreadsheet.

<table> creates a table

<tr> indicates start of each row

<td> each cell is represented by 

<th> table heading

<thead> headings of table 

<tbody> body should sit inside tbody 

<tfoot> footer of table

 

JS Chapter 3: Creating an Object

new keyword and object constructor creates a blank object. you can then add properties and methods

var object = new Object();

object.propertyName = propertyValue

this. keyword

ways to create objects: 1)  create object, then add properties and methods or 2) create an object with properties and methods

literal notation, object constructor notation

store data with variables and array

Document object

Global object: String object

Global object: Number object

Global object: Math object

Date object
```

#### Eighth Daily Reading
```
HTML Chapter 15: Layout

use <div> elements as containing elements to group sections together on a page

- HTML Boxes are either inline box or black-level box

- Block level starts on a new line. Inline flows in between surrounding text

- If a block level element sits inside another block level element, its known as its containing or parent element

- eg div

- Positioning schemes:

- Normal flow: every block level element appears on a new line, each new item lower than the previous one (default behavior)

- Relative positioning: Shifts element top-right-left-bottom from where it would be in normal flow but it doesn't affect the position of surrounding elements

- Absolute positioning: positions element in relation to containing element. Taken out of normal flow. Doesn't affect position of surrounding elements. Moves as user scrolls page

- Box offset:

- Fixed positioning: relative to browser window not containing element

- Floating element: out of normal flow, to the far left or right of containing box. Floated element becomes block-level element which other content can flow around

- Removing elements from normal flow can cause overlap, controlled by z axis

Layouts:

- Fixed width: do not change sizes as user increases or decreases size of browser window. measured in pixels

- Liquid layout: Stretch and contract as user increases or decreases size of browser window. uses percentages.

Layout grids:

- 960 pixel grid, 12 columns

- many variations possible

CSS frameworks

- helps create layout grids, styling forms, printer friendly versions, etc.

- checkout 960 Grid System at www.960.gs (Links to an external site.)

- one can have multiple css files in one page
```

#### Ninth Daily Reading
```
HTML Chapter 7: Forms

Adding text:

- text Input

- password input

- text area (text box)

Making choices:

- radio buttons (one of many options, can't uncheck)

- checkboxes ( select one or many, can uncheck)

- dropdown boxes

Submitting forms:

- submit buttons

- image buttons

- uploading files

How forms work:

- input selected by user, hits submit

- name of each form control and value sent to server

- backend processes it, may send to database

- server creates new page for user based on information received 

<form> action method id

<input> size type name maxlength

<textarea>

radio button: type="radio"

"checkbox"

- validation

HTML Chapter 14: Lists Tables & Forms

- Bullet point styles

- list-style-type

- list-style-image

- list-style-position

- list-style

Table Properties

-width 

-padding

- text-transform

- letter-spacing, font-size

- border-top, border-bottom

- text-align

- background-color

:hover

- border-spacing, border-collapse

- empty cell properties

Similar styling for text inputs for forms

JS Chapter 6: Events

Event types:

-load

-unload

-error

-resize

-scroll

Keyboard Events:

-keydown

-keyup

-keypress

Mouse Events

-click

-dbclick

- mousedown

-mouseup

-mousemove

-mouseover

-mouseout

Three ways to bind an event to an element:

- HTML event handlers

- Traditional DOM event handlers

- DOM level 2 event listeners

Traditional DOM event handlers:

element.onevent = functionName;
```

#### Tenth Daily Reading
```
JS Chapter 10: Error Handling and Debugging

- JS has an order of execution

Execution context:

- Global context: code in the script but not the function. Only one global context in any page

- Function context: Code run within a function. Each function has its own function context

- eval() - don't use or worry about it

Variable scope:

- global scope: variables declared outside a function that can be used anywhere

- function level scope: variable declared within a function, it can only be used within that function

The JS Stack:

- When a statement or function needs data from another function, the new function goes on the stack. Top of the stack is first to get done

- Last in first out

Preparation Phase - Execution Phase:

- functions and variables are created first

- that means you can call functions and variables before (above) where they are defined

--

- functions are linked to the objects they were defined within

- functions can access parent variables but not vice versa

Errors

- if JS generates an error, it throws an exception. at that point the interpreter stops and looks for exception handling code

- it continues looking in parent functions until global context, then breaks and creates error object

Error objects have the following properties:

- name

- message

- file number

- line number

7 error objects:

- error: generic error

- syntaxerror: syntax has not been followed

- referenceerror: tried to reference undeclared variable

- typeerror: unexpected data type

- rangeerror: numbers not in acceptable range

- urierror: encodeURI() and decodeURI() used incorrectly

- evalerror: eval() function used incorrectly

Debugging:

- Where is the problem?

- What is the problem?

- Use dev tools and console

- log data to console as you go

- group messages with console.group() 

- console.dir(object) to explore an object in the console

- pause execution of script with a breakpoint - chrome sources

Handling Exceptions:

- use Try, Catch (exception), Finally. If you think code will fail

- you can throw your own errors (but I don't get why you would)
```

#### Eleventh Daily Reading
```
HTML Chapter 16: Images

You can control the height/width of images in css

And position

Add background image with: background-image: url('#');

For example:

background: url('../images/showcase.jpg')
no-repeat center center/cover;
 
Be aware of high contrast images with text over them 
 
HTML Chapter 19: Practical Information
 
SEO Factors:
- page title
- url web address
- headings
- text
- link text
- image alt text
- page description
 
Use google analytics
```

#### Twelfth Daily Reading

What Google Learned From Its Quest to Build the Perfect Team:
```
Team dynamics matter a lot. 

"we all felt like we could say anything to each other"

Getting along better as a group > getting along better individually 

Group norms are deterministic of group performance. (Traditions, behavioral standards, unwritten rules)

- Members speak roughly the same proportion

- High average social sensitivity

Safe space to take risks

Goal is a team that is greater than its parts
```

```
EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS;

- Download Chart.js and copy Chart.min.js into working directory

- import in <head> with <script src='Chart.min.js'></script> (why not the body?)

- <canvas> element

- create line chart with:

new Chart(buyers).Line(buyerData);

- create pie chart with:

new Chart(countries).Pie(pieData, pieOptions);

- create bar chart with:

new Chart(income).Bar(barData);

^add data for charts

 

Chart.js Introduction:

Install like above. 1) include chart.js script reference 2) use <canvas> 3) follow documentation

 

Basic usage of canvas:

<canvas id="tutorial" width="150" height="150"></canvas>

"The <canvas> element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas."

 

Drawing shapes with canvas:

Canvas grid/coordinate space:

(0, 0) is the upper left corner. All elements are placed relative to this origin. 

<canvas> supports rectangles and paths (primitive shapes)

Rectangle functions:

fillRect(x, y, width, height)
Draws a filled rectangle.


strokeRect(x, y, width, height)
Draws a rectangular outline.


clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

Drawing Paths:

A path is a list of points, connected by segments of lines (can be curved)

1. create oath

2. use drawing commands to draw into path

3. use stroke or fill to render

Path functions:

beginPath() - creates new path

Path methods:

closePath()

stroke()

fill()

 

moveTo(x, y) - moves pen to coordinates to place a starting point somewhere else

(other functions for lines and arcs)

 

Applying styles and colors:

fillStyle = color
Sets the style used when filling shapes.


strokeStyle = color
Sets the style for shapes' outlines.

 

Transparancy:

globalAlpha = transparencyValue

 

Line styles and properties

 

Drawing text with canvas.js:

Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.


strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

```

#### Thirteenth Daily Reading

#### Fourteenth Daily Reading

#### Fifteenth Daily Reading
