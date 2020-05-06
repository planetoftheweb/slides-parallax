# ScrollMagic

- Trigger on position
- Pin elements
- Toggle CSS classes
- Easy parallax

> > Author Notes:

As your animations get to be more complex, it might be nice to install a library that makes some types of interactions easier. I really love the ScrollMagic library.

It makes some of the things we've been doing with pure javascript simpler, like for example triggering animation based on a scroll position.

You can also make elements stick around for a period of time.

It lets you toggle CSS classes on or off depending on scroll positions.

All this helps you more easily build parallax like effects.

To install it, you can go to their site and downdload a zip file, or get it from their Github repo.

The download has a ton of stuff what you need is in the scrollmagic folder. There's a minified version and a regular version. The minified version is better for production because it's smaller and he uncompressed is better during development.

If you open the minified version, you'll see that there are two parts. First is the library itselft. and then are a series of plugins.

The first two gsap and velocity help you make this library work better with two popular javascript animation libraries...gsap and velocity.

The next one will let you add indicators during debugging so that you can visualize triggers and when animations start and finish.

There's also a plugin to help scrollmagic work with jquery.

I've already added these for you in the js folder and in the lib folder. The scrollmagic javascript is in the main lib folder and the plugins are in the plugins folder.
