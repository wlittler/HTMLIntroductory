# CSS - Cascade Style Sheet

We all know that HTML elements helps us to structure the content on the page, grouping it semantically, but we all know that it isn't enough just that. We is when it comes to play CSS to make them more attractive and pleased to the eye by controlling HTML element on where they are positioned, color, and size. All of this is because CSS allow us to create rules that specify the element we what to target and the set of properties that are applied to that element.

## Syntax

Here is an example showing of a CSS rule, it is a rule applied to a p element. Pay close attention to the basic anatomy of this rule because one the common mistakes we make is forgetting to close on of the brackets, missing a semicolon, or a colon.

![CSS rule anatomy](/images/css-rule.jpg)

The selector tells which element the rule can be apply to. The declaration indicates what is going to be styled to the selected element. Property refers to the aspect of the element selected to change. Lastly the value indicates the setting chosen for that property. This seems a lot to memorize but in CSS this is repetitive, so you will encounter doing the same set of principles over and over again.

### CSS Selector

In CSS, selectors allows you to target the rules or styles to specific elements. CSS selector are case sensitive, so the must match exactly in order to be apply. Look at the [selectors list](http://www.w3schools.com/cssref/css_selectors.asp), have general knowledge of what they are capable of.

### CSS Properties

The properties are the setting of an element allowed to be modify. Here is a [list of properties ](http://www.w3schools.com/cssref/default.asp), have a general knowledge of what settings can be changed.

## CSS implementation

Now that we know how to create CSS rules we can create several CSS rules for a website. There are three possible ways to implement CSS rules, let's take a look:

### Inline style

At the opening tag of an element the attribute `style=""` is added. Within the quotes of the `style` declaration are added. Ex. - `<p style="color:blue;">This is a paragraph</p>`. This way does not required a selector since the rule is been apply to the element itself. This is one of the least recommended way to do styling. 

### Within HTML page

This is as simple as add a `<style>` element on the page and start writing CSS rules. This element is usually inside the `<head>` element. The limitation is that this style will only be available to this page and if you have multiple pages you would have to copy the styles and add them to the other files making it inefficient.

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

This is the most common way to add CSS rules to a website. It requires to have a file with extension .css named whatever you want (I would recommend a meaningful name) and a link tag from the HTML page specifying the file path. This is the most efficient way of integrating CSS to your HTML pages.

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

If two or more selector are the same and they all have the same property but with different value, the last one will take place.

### Specificity 

If a selector is more specific that the others, the more specific will take place over the more general selector.

### Important

You can add `!important` after any property value and it will not let other rules apply a different value even if they are the last rule or more specific.

<hr>

## Day 3 - Applying CSS to HTML elements

We will go over last week's homework, answering any question you might have. Then we will covering the three ways of implementation of CSS, analyzing pros and cons of each other.  We will experiment with the browser developer tool centered on the CSS manipulation that can be done to the DOM elements.

## Day 4 - In-deep CSS selector

We are already comfortable with what we can do with CSS using rules. The most complicated part it defining the right selector. We will discover at least 8 ways to do selection and build confident on those.