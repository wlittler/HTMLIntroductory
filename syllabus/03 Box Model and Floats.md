#Box Model

It is the term to describe the rules and properties surrounding of all HTML elements in the page. CSS treats each HMTL elements as if they lived in a box.
 
## Box model properties
There are 4 properties to control the box model of an element.
 
### Dimension
These are width and height of an element. By default these dimensions are determined by the content, but you can control them by specifying width/height in pixels, percentage, or ems. You can also specify a min width/height or max width/height of an element.

### Padding

Padding is the space between the content and the border of an element. Adding padding increases the width/height overall of an element.

### Border

Every element has a border even those it is not visible, because by default is 0px wide. If you have two element next to each other their borders will be touching.

### Margin

It is the space between each elements from the border of each. Margin allows to separate elements from each other.

Imagine you have a picture frame on a wall. The frame will be the border, the matting is the padding and the size of the picture is the width/height of the element. If you have more than one picture next to each other, then the separation distance will be the margin.

![Box Model example](/images/box-model.jpg)
 
 You can also see this in action. Open your default browser and get to the developer tool, from there select an element from the website, select layout and you will see all the values that an element's box model is been applied.
 
 ![Developer tool layout](/images/layout.gif)
 
 ## Block
 
 Of all the properties on the box model we can separate them into two important groups, content block, and containing block. These two groups are essential to understand when element no longer fits inside the parent element
 
 ### Content Block

The width/height, padding, and border of an element comes to determine the final or total dimension of an element.

### Containing Block

Represent the position in which the content block is located in relation to its parent. In this class we will concentrate on one of the properties; margin.

In class we will see what happen when either the content block or containing block no longer fits - called overconstrain. We will discover how the agent/browser interprets those constrains and what we can do in the event of that happening. 
 
<hr>

#Float
