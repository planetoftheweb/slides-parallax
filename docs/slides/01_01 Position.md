<!-- .slide: data-state="title" -->

# CSS Scrolling &amp; Parallax

---

# Position Property

<code class="code-primary fragment">static</code> <code class="fragment">fixed</code>
<code class="fragment">relative</code> <br> <code class="fragment">absolute</code>
 <code class="fragment code-warning ">sticky</code>

> > Author Notes:

There are several real important concepts that you'll need to understand when you're working with animation and one of those is how positioning works.

Positioning specifies how an element is going to be placed on the page. The easiest to understand is the default, which is static.

Static just means the object will be displayed in the same order as the HTML.

Fixed positioning means that the elemen will be displayed relative to the browser window, so it can go at the top or bottom left or right or some value relative to that.

Things get interesting with relative, you can position an element relative to where it would normally display by offsetting it in any direction.

Where it gets a bit confusing is with absolute, in this case the element is placed relative to it's first positioned parent. Most of the time this is used with relative positioning so that an absolute element will be positioned with a relatively positioned element.


To get a hint of how this works, we'll get started by building a navigation in for our project.
