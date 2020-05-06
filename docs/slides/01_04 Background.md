# CSS Backgrounds

- `background-OPT`
  - OPT: `color` `image` `repeat` `position` `size`<br>
     `attachment` `origin` `clip`

> > Author Notes:

Images are often targets of animations and sometimes it's best to place those images inside a background.

The background property has many options and you

`background-color` Color of the background
`background-image` One or more images or gradients
`background-repeat` How the background repeats
`background-position` Position in the container
`background-size` Size of the background
`background-attachment` How the background scrolls
`background-origin` Positioning with padding/borders
`background-clip` How image is cut off

---

# background-repeat

- <code class="code-success">repeat</code> `repeat-x` `repeat-y` `no-repeat` `space` `round`


> > Author Notes:

Backgrounds repeat by default, and you can control how that works. Normally, you'll be working with a single image, so this will set to no-repeat, but you can also repeat horizontally, vertically and the last two try to repeat without leaving any partialy cropped images. Space creates a bit of whitespace around copies and round doesn't


---

# background-position

- One or two values
- Keywords: <code class="code-success">left</code> `right` <code class="code-success">top</code> `bottom`  <code class="code-warning">center</code>
- `xpos` `ypos`, <code class="code-warning">50%</code>

> > Author Notes:


---

# background-size

- Keywords:<br><code class="code-success">auto</code> `width/height` `cover` `contain`
- Percent or Pixels, auto default

> > Author Notes:

Auto is the default, which means the image is displayed at it's original size.

You can also type in a width and or a height value, which are typically done in percentages, pixels but can be other length units. If you include only one value, then it assumes it's the width and the height will be set to auto.

There are two special properties, cover resizes the background to cover the entire container proportionally. This is one of the most popular settings.

There is also one called contain, that resizes the background image to make sure it's fully visible

---

# background-attachment

- <code class="code-success">scroll</code> `fixed`

> > Author Notes:

The attachment is how the background behaves when you scroll the mouse The default is for the background to scroll, but you can also have the image stay put with the fixed option...it's like setting the positioning of your image to the fixed option. That can give you an easy scroll effect, but it doesn't work with a background-size set to cover. Bummer

---

# Background Combo

```css
background: bg-color bg-image position/bg-size
bg-repeat bg-origin bg-clip bg-attachment;
```

> > Author Notes:

For animating purposes, you'll probably want to set up individual properties when you want to animate a background in relationship to the content.
