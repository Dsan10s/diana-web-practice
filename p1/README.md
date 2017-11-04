# Part 1

In this part we defined the basic structure of an html application.  Look at
index.html.  Here we defined 3 different elements:

- `<html>`
	- Your html application must be wrapped in this tag.
- `<head>`
	- Reference elements will be put in here.
- `<body>`
	- Elements that define the how the application looks will go in here.

We defined `<head>` and `<body>` inside of `<html>`.  This makes these elements
_children_ of the `html` element.

In some of the next sections you'll learn about other elements that have
different purposes.

You'll also notice the use of text wrapped in something like this:

`<!-- -->`

Any text in html wrapped in that will not be executed.  You can use this to
write helpful notes, and is known as a _comment_.

You'll also notice that each element was defined with an open bracket `<`, a
word, and then a close bracket `>`.  This is known as a _tag_ for an element.
Almost every element needs an opening tag, and a closing tag.  With closing
tags, you do the same thing as opening tags, but put a `/` after the open
bracket.  For example:
- `<body>` is the opening tag for the `body` element.
- `</body>` is the closing tag for the `body` element.
