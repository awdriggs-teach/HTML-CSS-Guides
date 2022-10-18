# Shapes
Everything in HTML is in a box, but we can round the corners and even make circles.

Here is some basic HTML.
```html
<img src="grumpy.jpg" class="rounded">
```
This is how our page looks.

![Cat Image](./media/rounded1.png)

Just adding the class name won't do anything. We can add some magic with CSS.

```css
.rounded {
  border-radius: 10%;
}
```

Now we see that the corners of the image have been rounded.

![Cat Image](./media/rounded2.png)

We can keep going! If we want a perfect circle with can increase the rounding percent to 50%.

```css
.rounded {
  border-radius: 50%;
}
```
 
Now we get this!

![Cat Image](./media/rounded3.png)

