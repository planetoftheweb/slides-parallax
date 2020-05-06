# CSS Animation Properties

- `animation-OPT`
  - OPT: `name` `duration` `delay` `timing-function` <br>`iteration-count`
     `direction` `fill-mode` `play-state`

> > Author Notes:

Let's take a look at the properties that affect how we can animate. Just like with background there are many classes as well as a combination class. The individual classes are:

name so that you can specify the keyframe name that this animation will use.

duration is of course how long the animation will last. You can use seconds or milliseconds

delay tells the browser to wait a certain amount of time before the item is animated.

timing function controls the speed acceleration or curve of the animation.

iteration count defines how many times the animation should play.

animation-direction determines if the animation should play in reverse or some other sequence.

fill-mode determines what happens when the animation finishes executing, so you can control wether the last frame played is frozen when the animation ends.

You can use play-state to pause or play the animation and that's usually done with javascript.

Let's take a look at a few of the interesting properties in depth.

---

# animation-timing-function

- `linear` <code class="code-success">ease(-in)(-out)</code><br>`step(-start)(-end)`<br> `steps(number,start,end)`<br>`cubic-bezier(n,n,n,n)`

> > Author Notes:

Linear means that the animation will not accelerate at all, but have a consistent speed.

The default is the ease method, which is like the ease-in-out method. I find the words ease and in and out confusing, so I like to replace the word ease with slow and the word in with beginning and the word out with end.

So ease-in means slow at the beginning, ease out means slow at the end.

The steps are ways of creating animations that are not smooth, but advance in measurable steps. Think of how a second hand on a clock doesn't always move smoothly but sometimes jumps from one position to another.

The final option is the Cubic-Bezier, which lets you create a custom movement function using bezier curves. If you remember the numbers on our hero.svg files, the monsters are drawn in this way.

One great place to visualize cubic bezier and how it compares to other easing functions is https://cubic-bezier.com/#0,0,1,1 from the awesome Lea Verou. You can see that the numbers in a cubic-bezier function are nothing more than two points related to the progression of an animation over time.

---

# animation-iteration-count

- <code class="code-success">1</code> or `number`
- `infinite` keyword

> > Author Notes:

This is how many times the animation plays, and of course, the default is one, but you can also use the keyword infinite, which means the animation will play forever.

---

# animation-direction

 <code class="code-success">normal</code>  `reverse` `alternate`  `alternate-reverse`

> > Author Notes:

This controls how the frames are played, the default is that they play in a normal sequence from start to finish. You can run the frames in reverse order as well. If you chose alternate, then the animation will play forwards, then backwards. alternate-reverse means it plays backwards and then forwards.

---

# animation-fill-mode

 <code class="code-success">none</code> `forwards` `backwards` `both`

> > Author Notes:

The default value is to play the animation forwards. You can also choose to play the animation backwards
