# Welcome to the Resume File

# HTML

we have leearend quite a few more html elements

<div></div>: it's a container mainly used in the CSS side of things
<em></em>: this element emphasizes words or phrases
<strong></strong>: gives some importance to the text inside it

<hr/>: it's a void element , it displays a divider between two sections of different content

<article></article>: article elements commonly contain multiple elements that have related 
information.

We have new Attributes that we can create to facilitate CSS styling like:

- class attribute : we can taret it to style any other element with the same class attribute value

- id attribute : same as the class attribute , but while styling we will mostly use the class attribute

# CSS

as we have a project folder structure where we leave index.html as the route and place any other HTML document on other folders inside our project , so we get the CSS folder as well now ewe can link it with the index.html route

- To Center the content of the h1 element by setting its text-align property to the value center.

  eg:  
   h1 {
  text-align: center;
  }

  h1: selector
  text-align: property
  center: value

if you have 2 or more selectors with the same styling you can just
for example :
h1,p{
color : blue;
}

For the styling of the page to look similar on mobile as it does on a desktop or laptop,
you need to add a meta element with a special content attribute.

Add the following within the head element:

Example Code

<meta name="viewport" content="width=device-width, initial-scale=1.0" />

let's talk about the CSS reset first later:

<!-- the CSS reset will go here -->

we learned that block level element take up the entire width of their parent element
in order to get block level element on the same line we need to set their display property to : inline-block

and if we want an inline level element like img to take up the entire width of its parent we can set its display property to : block

let's talk properties:

- width : this help us to manipulate the space we need to use horizontally
  we can set it in %, px, nad some other stuff
- max-width : helps to prevent the container to growing bigger than the value set by the max-width property
  <!-- - margin: todo -->
  <!-- - padding todo -->
  <!-- - border todo -->

  all we know for now is that they can have top, bottom, left, and right

- height : this help us to manipulate the space we want to use vertically

- background-image: we need to set the url() or the path leading to our pictures on the project

- font-family: changes the font for the text

You can add a fallback value for the font-family by adding another font name separated by a comma.
Fallbacks are used in instances where the initial is not found/available.

let's talk about how to target created classes on the HTML side so we can use it on the CSS style

- for classes use : . then class name
- for ids use : # then id name
  that's all we have for now regarding that

NB:

- to center a div on the page just
  set the margin-left and margin-right properties to auto for both

- to center text inside a container just text-align : center with the concerned selectors

Let's talk pseudo-selector
we don't have much on the subject yet but aight

Example note:
The default color of a link that has not yet been clicked on is
typically blue.
The default color of a link that has already been visited
from a page is typically purple.
to change it:

- a:visited { propertyName: propertyValue; }.

- You change properties of a link when the mouse hovers over them by using
  a pseudo-selector that looks like a:hover { propertyName: propertyValue; }.

- You change properties of a link when the link is actually being clicked
  by using a pseudo-selector that looks like
  a:active { propertyName: propertyValue; }.

# What Stood out to me :

It would be nice if the vertical space between the h2 elements and
their associated icons was smaller.
The h2 elements have default top and bottom margin space,
so you could change the bottom margin of the h2 elements to say 0 or another
number.

There is an easier way, simply add a negative top margin to the img elements
to pull them up from their current positions.
Negative values are created using a - in front of the value.
To complete this project,
go ahead and use a negative top margin of 25px in the img type selector.

many things stood out to me
like creating classes or IDs : are actually attributes and can be targeted on the CCS side to make styling much easier

CSS is there to help the structure of HTML have a live , beauty and charm

we have learn so many new selectors to be framk right now it's night and day
but with few practices going forward i hope to master those and many more

on top of my head all HTML elements can be seen as selectors on the CSS side , that eliminates a lot of guessing

so the main thing is to have an understanding of the concept in which each property is used for

some properties i can list on top of my head are:

width, height,(their-max), background-color, background-image, margin, padding, border(top,bottom,left,right), float, font-family, font-size, font-style, a:visited, a:hover, a:active("pseudo-selector"),
display, yeah i probably missed some but yeah that's all i got for now

# Notes and Structure of the Project:

HTML Boilerplate
have a div element (a container the main and footer element will be included here as well)

h1 with text : CAMPER CAFE
and a p element
then comes an hr element it's a void element it creates an Horizontal line

then we have the 1st section
with a h2 with text : Coffee
followed with a img element

then we have 5 article element with 2 nested p element inside it

then we have another section with a h2 element with text : Desserts
followed with an img element

then we have 5 article element with 2 nested p element inside it

the catch here is that we need the price to be on the right of the page and the flavors and desserts on the left of the page

we will need a float property on the .price and .flavors and .dessert

then we have an hr element

then the footer
that will include 2 p element , the first will be a nested p element inside the a
and the next P will just be a a normal p element

new text Nigga
