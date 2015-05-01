#CSS Box Model

Box Model is the term used to describe the rules and properties surrounding all HTML elements in the page. CSS treats each of the HMTL elements as if they reside in a box. The two-dimensional box contains, from the outermost layer to the innermost layer, a margin, a border, padding, and content. The box model is a model for adding borders and space around elements. 
 
## Box model properties
There are 4 properties to control the box model of an element. These are content, padding, borders and margins. 
 
### Dimensions
These are width and height of an element, since we are working in two dimensions. By default these dimensions are determined by the content, but you can control them by specifying width/height in pixels, percentage, or ems. You can also specify a min width/height or max width/height of an element.

### Padding

Padding is the space between the content and the border of an element. Adding padding increases the width/height overall of an element.

### Border

Every element has a border whether or not it is not visible, because by default is 0px wide. If you have two elements next to each other, their borders will be touching.

### Margin

The margin is transparent and defines the space around the border. Margins allow you to separate elements from each other.

Imagine you have a picture frame on a wall. The frame will be the border, the matting is the padding and the size of the picture is the width/height of the element. If you have more than one picture next to each other, then the separation distance will be the margin.

![Box Model example](/images/box-model.jpg)
 
You can also see this in action. Open your default browser and get to the developer tool. From the developer tool, select an element from the website, then select layout, and you will see all the values represented in the box model applied to a given element.
 
 ![Developer tool layout](/images/layout.gif)
 
 ## Block
 
We can separate the properties of the box model into two important groups: content block and containing block. These two groups are essential to understanding when an element no longer fits inside the parent element.
 
 ### Content Block

The width/height, padding, and border of an element determines the final or total dimension of an element.

### Containing Block

Containing blocks represent the position in which the content block is located in relation to its parent. In this class we will concentrate on one of the properties: margin.

In class we will see what happens when either the content block or containing block no longer fits - called overconstraint. We will discover how the agent/browser interprets those constraints and what we can do in the event that happens. 
 
<hr>

#Float
