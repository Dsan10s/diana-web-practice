# Part 1

## index.html
```
<html>
	<head>
		<!-- Below we define our first reference, a reference to a css file -->
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<div id="mainContainer"></div>
	</body>
</html>
```

## style.css
```
#mainContainer {
	width: 100px;
	height: 100px;
	background-color: red;
}
```

## Instructions
Open a web browser and type `file:///`.  This will allow you to navigate your
computer's file browser using your web browser.  Find where you downloaded this
repository, and open `p2` and then open `index.html`.  You should see a red
square in your browser.

## Explanation

In this part we added a couple of things:
- `<link>` tag in the `head` element
- `rel` and `href` _attributes_ in the `<link>` tag
- A `div` element in the `body`
- An `id` _attribute_ in the `div`
- We also added a `style.css` file, and referenced it using our `link`

Let's walk through each addition:

### `link` and _attributes_
The `<link>` tag is a common way to include css code in your application,
while keeping that code in a separate file.  In order to declare what type of 
file we're getting, and where the file is, we use something called
_attributes_.  _Attributes_ are things that we add within a tag, to tell it
certain things about itself.  Whenever you include a css file, you always set
the `rel` attribute of a `link` tag to `"stylesheet"`.  Then you add an `href`
attribute, and set that equal to the path of the file.  Since the file is in the
same directory as index.html, I only have to specify the name of the file.  If
you are unfamiliar with directories, don't worry, just put all your files in the
same folder and it works the same.

### `div`
`div` elements are a very commonly used tag.  They are probably the most generic
tags in html.  With any tag, you can add style to it.  In this case, our `div`
now has a width and height of 100px, and is red.  We set how this looked in our
style.css file, which index.html knows about thanks to our `link` tag.  But how
did we set this style?  This was done using our `id` tag that we added to the
div.

### `id`
`id` is an attribute that you can add to any display element.  This will allow
you to reference a specific html element.  In our case, we added an `id` tag to
our `div` to give it an id of `mainContainer`.  This allowed us to reference
this specific `div` by using the syntax `#mainContainer` in style.css.  The `#`
specifies that we're talking about an `id`.
