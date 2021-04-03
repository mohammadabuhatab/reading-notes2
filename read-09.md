## Form Controls
There are several types of form controls that
you can use to collect information from visitors
to your site:
* ADDING TEXT
* Making Choices
* Submitting Forms
* Uploading Files

<hr>

1. ***form:***
Form controls live inside a
`<form>` element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

2. ***action:***
Every `<form>` element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.

3. ***method:***
Forms can be sent using one of
two methods: get or post.

4. ***input:***
The `<input>` element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.

5. ***textarea***
The `<textarea>` element
is used to create a mutli-line
text input. Unlike other input
elements this is not an empty
element. It should therefore have
an opening and a closing tag.

<hr>

## lists
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
rules that apply to the `<ul>` and
`<li>` elements.
The example on this page also
shows the use of the margin
property to increase the vertical
gap between each item in the
list.

<hr>

## table

You have already met several
properties that are commonly
used with tables. Here we will
put them together in a single
example using the following:
width to set the width of the
table

**padding** to set the space
between the border of each table
cell and its content

**text-transform** to convert the
content of the table headers to
uppercase

**letter-spacing**, **font-size**
to add additional styling to the
content of the table headers
border-top, border-bottom
to set borders above and below
the table headers

**text-align** to align the writing
to the left of some table cells and
to the right of the others
background-color to change
the background color of the
alternating table rows

<hr>

## Events

Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).

Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.

When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.

You can use event delegation to monitor for events
that happen on all of the children of an element.

The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

<a href="README.md">HOME</a>
