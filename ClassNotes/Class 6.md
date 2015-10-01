### Class 6 - HTML Intro to Front End - Wednesday, 9/30/2015

Took Quiz

1. Left, Right, None, Inherit

2. Stack on top of each other

3. Normal Document Flow

4. Container collapse

5. Create a layout

6. Yes, they would float because it was more specific in the selection


If you have more than one floating element inside a container that is within the normal document flow, the container will collapse.

### Fixing Container Collapse

1. Add an element after the floated elements and clear that element in the css.
2. Add the overflow: hidden; to the parent element.
3. Make the parent element float as well.
4. Add a class (something like class="clearfix") to the parent of floated elements with the style of:

```html
.clearfix:after {
  content: ""; 
  display: block;
  clear: both;
}
```


