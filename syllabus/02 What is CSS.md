# CSS - Cascade Style Sheet

We all know that HTML elements help us to structure the content on the page, grouping it semantically, but we all know that isn't enough by itself. We need CSS to make our pages more attractive and pleasing to the eye by controlling HTML elements with regard to position, color, and size. CSS allows us to create rules that specify the element we want to target and the set of properties that are applied to that element, such that the way the html elements are displayed is defined by CSS. This simplifies web development by removing the need to add tags to every page. 

## Syntax

Here is an example of a CSS rule applied to a p element. Pay close attention to the basic anatomy of this rule because some of the common mistakes we make include forgetting to close one of the brackets, missing a semicolon, or leaving out a colon.

![CSS rule anatomy](/images/css-rule.jpg)

The selector tells which element to which the rule applies; in other words, it specifies the element you want to style. The declaration indicates what is going to be styled to the selected element. Property refers to the aspect of the element selected to change (as in color). Value indicates the setting chosen for that property (as in yellow). This seems a lot to memorize but in CSS this is repetitive, so you will be applying the same set of principles over and over again.

### CSS Selector

In CSS, selectors allows you to target the rules or styles to specific elements. CSS selectors are case sensitive, so they must match exactly in order to be applied. Look at the [selectors list](http://www.w3schools.com/cssref/css_selectors.asp), build your general knowledge of the use of selectors for manipulating elements.

### CSS Properties

The properties in CSS define how the styles will appear on your web page. For example, CSS font properties define all aspects of font, such as font size, boldness, and family. Here is a [list of properties ](http://www.w3schools.com/cssref/default.asp), so you can build your general knowledge of what settings can be changed.

## CSS implementation

Now that we know how to create CSS rules we can create several CSS rules for a website. There are three possible ways to implement CSS rules. Let's take a look:

### Inline style

At the opening tag of an element the attribute `style=""` is added. Within the quotes of the `style` attribute, declarations are added. Ex. - `<p style="color:blue;">This is a paragraph</p>`. This way does not require a selector since the rule is being applied to the element itself. This is one of the least recommended ways to do styling. 

### Within HTML page

This is as simple as adding a `<style>` element on the page and starting to write your CSS rules. This element is usually inside the `<head>` element. The limitation is that this style will only be available to this page and if you have multiple pages, you would have to copy the styles and add them to the other files, making it an inefficient method of styling.

```html

<head>
    <style>
        p {
            color: blue;
        }
    </style>
</head>
<body>
    <p>This is a paragraph</p>
</body>

```

### External CSS file

This is the most common way to add CSS rules to a website. It requires you to have a file with extension .css named whatever you want (I would recommend a meaningful name) and a link tag from the HTML page specifying the file path. This is the most efficient way of integrating CSS to your HTML pages.

HTML file:
```html
<!doctype>
<html>
    <head>
        <title>Using a external CSS file</title>
        <link rel="stylesheet" href="css/my-style.css">
    </head>
    <body>
        <p>This is a paragraph</p>
    </body>
</html>
```

CSS file:
```css
 p {
   color: blue;
}
```

## CSS Rule Cascade

What would happen if there are two or more rules applying to the same element? It is important to understand which takes precedence.

### Last rule

If two or more selectors are the same and they all have the same property but with different values, the last one will take place.

### Specificity 

If a selector is more specific than the others, the more specific will take place over the more general selector.

### Important

You can add `!important` after any property value and it will not let other rules apply a different value even if they are the last rule or more specific.

<hr>

## Day 3 - Applying CSS to HTML elements

We will go over last week's homework, answering any questions you might have. Then we will covering the three ways of implementing CSS, analyzing the pros and cons of each.  We will experiment with the browser developer tool, focusing on the CSS manipulation of the DOM elements.

## Day 4 - In-deep CSS selector

We are already comfortable with what we can do with CSS using rules. The most complicated part is defining the right selector. We will discover at least 8 ways to do selection and build confidence with those.
