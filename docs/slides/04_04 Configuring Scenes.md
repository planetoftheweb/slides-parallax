# Controlling Scenes

- `triggerElement`
- `triggerHook`
- `offset`
- `duration`
- `reverse`

> > Author Notes:

Let's dig into how you can configure your how your scenes work. We already used the triggerElement in the last video, it lets you identify the DOM element that triggers the animation. If you don't specify one, the animation will be set to start at the beginning of the page.

You may have noticed that the triggers are positioned by default on the center of the viewport, you can change that with triggerHook, so that the triggers happen at the beginning or end of the viewport. This cab be a number between 0 and 1, 0 meaning the top of the page and 1 at the end. The default is the center, which is .5 and you can use the keywords onEnter, onCenter or onLeave.

You can also use offset if you want the to add a bit of space around the trigger hooks moving them down by a pixel amount, which can be positive or negative.

Duration lets you determine when the beginning and ending of the animation takes place. This is more useful when you have an animation that is based on scrolls.

Reverse determines what happens after the application takes place, if it will reverse when you scroll up. Again, this makes a bit more sense when scrolling.
