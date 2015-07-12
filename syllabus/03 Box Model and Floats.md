# CSS Box Model

Box Model is the term used to describe the rules and properties surrounding all HTML elements in the page. CSS treats each of the HMTL elements as if they reside in a box. 

## Box model properties

There are 4 properties to control the box model of an element. These are dimensions, padding, borders and margins. 
 
### Dimensions

These are width and height of an element, since we are working in two dimensions. By default these dimensions are determined by the content, but you can control them by specifying width/height in pixels, percentage, or ems. You can also specify a min width/height or max width/height of an element.

### Padding

Padding is the space between the content and the border of an element. Adding padding increases the width/height overall of an element.

### Border

Every element has a border whether or not it is visible. If you have two elements next to each other, their borders will be touching.

### Margin

The margin is transparent and defines the space around the border. Margins allow you to separate elements from each other.

Imagine you have a picture frame on a wall. The frame will be the border, the matting is the padding and the size of the picture is the width/height of the element. If you have adjacent pictures, the separation distance will be the margin.

![Box Model example](/images/box-model.jpg)
 
You can also see this in action. Open your default browser and get to the developer tool. From the developer tool, select an element from the website, then select layout, and you will see all the values represented in the box model applied to a given element.

![Developer tool layout](/images/developer-tool.gif)

## Block
 
We can separate the properties of the box model into two important groups: content block and containing block. These two groups are essential to understanding when an element no longer fits inside the parent element.

### Content Block

The dimensions, padding, and border of an element determines the final or total dimension of an element.

### Containing Block

Containing blocks represent the position in which the content block is located in relation to its parent. In this class we will concentrate on one of the properties: margin.

<hr>

# Float

The use of floats will allow us to alter the normal document flow of elements by altering their position. The normal document flow positions the elements one on top of another, but using float on an element will move it to the rightmost or leftmost edge of its parent.

In class we will be floating elements left and right and we will see the consequence of dealing with *container collapse* and *column collapse.* 

### Container collapse

It occurs when the parent element cannot see the children because they are removed from the normal document flow, so it collapses up until it finds an element that is part of the normal flow. If not, then it collapses entirely.

[Example of container collapse](/exercises/week-3/container-collapse.html)

### Column collapse

A column collapse happens when the floating element runs out of space from its parent container so that the element(s) will resume in another line.

[Example of column collapse](/exercises/week-3/column-collapse.html)

<hr>

## Day 5 - Working with Box Model

We will go over last week's homework, answering any questions you might have. This day we will be covering the box model properties and the consequences of manipulating these properties. In class we will see what happens when either the content block or containing block no longer fits - called overconstraint. We will discover how the agent/browser interprets those constraints and what we can do in the event that happens. 

### Homework day 5

Working on it

## Day 6 - Manipulating the normal document flow

We will go over day 5 homework, answering any questions you might have. In class we will be covering how can we manipulate the position of the elements by floating them to the left or right and the consequences that it brings such as container and column collapse.

### Homework day 6

You need to fix [container-collapse-problem.html](/exercises/week-3/container-collapse-problem.html). You are going to notice that the parent contaner has no color behind its children. Modify the CSS so you can see the background of the parent element.

You need to fix [column-collapse-problem.html](/exercises/week-3/column-collapse-problem.html). You will need to fix the page to make the fourth box fit in the same row. 