
# Objects
 group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

<img src=./images/23.PNG></img>

# The Document Object Model (DOM) 
specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

### Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

If a method can return more than one node, it will
always return a Nodelist, which is a collection of
nodes (even if it only finds one matching element).
You then need to select the element you want from
this list using an index number (which means the
numbering starts at 0 like the items in an array).

<a href="README.md">HOME</a>