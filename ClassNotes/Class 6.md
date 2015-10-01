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

### The BOX Model (dun dun dunnnnn)

All elements on your page are represented as boxes.  

These boxes are broken down into 4 sections:

1. dimension (width/height)
2. padding
3. border
4. margin

Dimension is the width and height of the element.
Padding is the space between the content and the border.
Border is border between padding and margin. Unique to border is the way we style it in the css:
  border: 1px solid #345678;   this will set your border to have 1px width, be a solid line, and have a #345678 color.
Margin is the space between your element and the surrounding elements.

Multiple variations to setting box model values:
The order to set them is top, right, bottom, left.
padding: 20px; is the same as 20px 20px 20px 20px;
padding: 20px 10px; is the same as 20px 10px 20px 10px;
padding: 20px 10px 5px; is the same as 20px 10px 5px 20px;

You may find yourself having to declare only one side of property. You can then use -direction like padding-left: or margin-bottom: to set only one of the properties.

You can use different measurements within (like padding: 10px 20%;), but you should generally try to be consistant with your measurements.


