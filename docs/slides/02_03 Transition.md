# CSS Transition Properties

- `transition-OPT`
  - OPT: `property` `duration` `delay` `timing-function`

> > Author Notes:

Transitions are a simple way of animating CSS properties. Like background it can be called with a single transition combo property or there are several individual properties you can control.

with the property keyword, you can control which CSS properties are modified during the animation.

duration tells the browser how long the transition will last and that can be in seconds or milliseconds, delay allows you to start a transition after a pre-defined period of time.

Timing function controls the speed of the animation.

---

# transition-property

- `none` <code class="code-success">all</code> `property(ies)`

> > Author Notes:

You can specify none if you want to clear a property from animating and the default, which is to animate all properties. You can also specify one or more properties separated by commas.

So for example, you can choose to animate the width or the height of an element or also the transformed element.


---

# transition-timing-function

- `linear` <code class="code-success">ease(-in)(-out)</code><br>`step(-start)(-end)`<br> `steps(number,start,end)`<br>`cubic-bezier(n,n,n,n)`

> > Author Notes:

Linear means that the animation will not accelerate at all, but have a consistent speed.

The default is the ease method, which is like the ease-in-out method. I find the words ease and in and out confusing, so I like to replace the word ease with slow and the word in with beginning and the word out with end.

So ease-in means slow at the beginning, ease out means slow at the end.

The steps are ways of creating animations that are not smooth, but advance in measurable steps. Think of how a second hand on a clock doesn't always move smoothly but sometimes jumps from one position to another.

The final option is the Cubic-Bezier, which lets you create a custom movement function using bezier curves. If you remember the numbers on our hero.svg files, the monsters are drawn in this way.

One great place to visualize cubic bezier and how it compares to other easing functions is https://cubic-bezier.com/#0,0,1,1 from the awesome Lea Verou. You can see that the numbers in a cubic-bezier function are nothing more than two points related to the progression of an animation over time.
