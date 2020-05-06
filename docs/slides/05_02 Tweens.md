# GSAP Tweening

- `var tween = TweenMax`
- `.from(target, {vars})`
- `.to(target, {vars})`
- `.fromTo(target, {vars}, {vars})`

> > Author Notes:

To get started using GSAP tweens, you create a new TweenMax object, the most common actions you can do with tweens is set up a starting state to animate from using .from.

An ending state to animate to with .to

Or two states to animate from and to. You can pass along a number of variables that determine how the tweens work.

---

# Tween Vars

- CSS properties
- `duration`
- Other

> > Author Notes:

These variables can modify css properties like opacity and position.

Although you can also specify a duration with GSAP, ScrollMagic will just ignore that and use it's own duration parameter.

You can also specify additional methods and properties which are not really part of CSS, so for example, you can use the ease property, which controls the acceleration of your animation. Let's take a look at how this works.


---

# Activating Tween

- `.setTween(tween)`

> > Author Notes:

To get this working with Scrollmagic we ad this into our Scene by adding the setTween method and then specifying our tween,

Let's take a look at how this works.
