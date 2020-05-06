# Objects and Viewports

- `window.innerHeight`
- `window.innerWidth`
- `el.getBoundingClientRect()`

> > Author Notes:

As you can tell, controlling objects is largely based on where the objects are in relationship to the page or the viewport, but there's another consideration...and that's making sure we only animate when an object is on screen.

We took at peek at one of the properties that is relevant here in the last video and we're going to work with it again now. The innerHeight of course tells you the height of the current window, the innerWidth shows you the inner width. As user resize the window these values will adjust.

We can combine this with the getBoundingClientRect method that gives use the position of the element relative to the viewport, as well as the width and height.

With these method and properties in our toolbelt, lets create a function that tells us wether an element is showing up on screen.
