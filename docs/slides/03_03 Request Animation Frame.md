# Syncing Animation

- `requestAnimationFrame()`
- Calls a function
- `DOMHighResTimeStamp`


> > Author Notes:

There is a special function you can use to make sure that your animations will sync properly to the browser called requestAnimationFrame.

This method can call another function that will perform your animation.

The callback will be passed a timestamp of when the animation happened in relation to the beginning of the document's lifetime, but you don't have to use that.

---

# Element Positioning

- `getBoundingClientRect()`
- Returns rect
  - `left` `top` `right` `bottom`<br>`x` `y` `width` `height`

> > Author Notes:

Another useful method we can use is the getBoundingClientRect, which we can use to determine the position of an object

When we combine this with requestAnimationFrame, we can calculate the position when the page is scrolled.

If you need to make this work in older browsers, take a look at this gist from the great Paul Irish.
