# CSS Keyframes

```
@keyframes name {
  selector { styles }...
}
```

- selector:
  - `0-100%`
  - `from`...`to`

> > Author Notes:

Keyframes let you describe more complex animation sequences than transitions. You define them with a special AT sign keyframe section and then inside that, you can place one or more keyframe-selectors that when the animations will take place.

They can be either a number from 0%, which would be the beginning or 100% which would signify the end. You can also use the keywords from to signify 0% or to which stands for 100%.

Inside each of the keyframe selectors, you define how the animation will change at that point in time by adding properties that modify the element.
