# Pinning

- `setPin(el, opt)`
- `pushFollowers` opt
- `duration`

> > Author Notes:

Pinning allows objects to remain in place for a period of time and then it will released again. You pass along the selector of the element that you want to pin.

There's also an option called pushed followers which can be set to false. That's because pinning an element will create a gap in your content the size of the duration, which might not be what you want.

Of course the scene duration property controls how long the pin will hold for. If you don't specify a duration, the pin will never be released, unless you scroll back past the trigger position.
