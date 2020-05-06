# CSS Transforms

<code class="fragment" style="margin-bottom: 10px">transform:</code><br>
  <small  style="font-size: 1.3rem">
  <code class="code-success fragment" style="margin-bottom: 10px"> none</code><br>
  <code class="fragment" style="display: block; margin-bottom: 10px">`scale(3d)(x,y,z)`</code>
  <code class="fragment" style="display: block; margin-bottom: 10px">`rotate(3d)(x,y,z)`</code>
  <code class="fragment" style="display: block; margin-bottom: 10px">`skew(x,y,z)`</code>
  <code class="fragment" style="display: block; margin-bottom: 10px">`translate(3d)(x,y,z)`</code>
  <code class="fragment" style="display: block; margin-bottom: 10px">`perspective(n)`</code>
  <code class="fragment" style="display: block; margin-bottom: 10px">`matrix(3d)(n,n,n,n...)`</small></code>
  <div class="fragment">separate with spaces</div>
  <div class="fragment">%, px, deg</div>

> > Author Notes:

The transform project lets you modify an element in a few different ways without affecting the rest of the layout.

The default value is of course no transformation.

But there are lots of other ones, you can apply scaling, which means changing the size of the item, by using the scale value.

You can also rotate an element or skew an element, which means tilting it.

translate means moving an object a certain distance.

You can use a single value for these transformations, so for example, you choose to scale the entire object a by a certain amount or choose to only do it in an X or Y axis. That means you would use the scaleX or scaleY keyword instead of regular scale.

There are also different versions for if you want to do things in two or three dimensions so adding the 3D keyword at the end would let you do this.

There is a special perspective property that lets you define how far away the object is from the user.

matrix lets you create a complex mathematical transformation usin 4 sets of 4 numbers.

A couple of notes, you can define multiple tranformations by separating them with spaces

Finally, you should use appropriate measurements. For some transformations like translate, a pixel amount of how far to move something makes sense, but you can also use percentages. For

---

# Other Properties

- `transform-origin:` x, y, z
- `perspective-origin:` x, y, z
- `transform-style:` <b>flat</b> | preserve-3d
- `backface-visibility:` <b>visible</b>|hidden

> > Author Notes:

The transform origin property lets you define how far away an element is placed from the view, it gives 3d objects a bit more depth.

Perspective origin lets you define where the user is looking at the 3-d positioned element from.

transform style lets you determine if the child elements that have been 3d transform retain their 3d transformations.

Since you can rotate object in three dimensions backface visibility lets you control if you can see the backside of a 3d rotation.

If you want to visualize
