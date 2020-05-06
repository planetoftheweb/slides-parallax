# Pseudo Classes

```css
selector:pseudo {
  property:value;
}
```

<code class="fragment">:hover</code>

> > Author Notes:

To show you how positioning works, I'm going to build some styles using a special category of classes called pseudo classes.

Pseudo classes lets you define the how an element looks when it's in a certain state. The one we're interested is the hover state...when a user places the mouse over some element, but there are dozens of pseudo elements.




---

# Pseudo Elements

```css
selector::pseudo-element {
  property:value;
}
```

<code class="fragment">::before</code> <code class="fragment">::after</code>

> > Author Notes:

To show you how positioning works, I'm going to build some styles using a special category of classes called pseudo elements.

Pseudo elements let you take an element and modify certain parts of that element, or in our case create new elements related to certain elements.

The pseudo elements we're interested in are called before, which lets you create an element before our selected element and after which lets you create one after an element.

Here's what the code looks like. You specify a selector and then use the pseudo element name to modify properties.
