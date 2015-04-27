# CSS -  Cascade Style Sheet

We all know that HTML elements helps us to structure the content on the page, grouping it semantically, but we all know that it isn't enough just that. We is when it comes to play CSS to make them more attractive and pleased to the eye by controlling HTML element on where they are positioned, color, and size. All of this is because CSS allow us to create rules that specify the element we what to target and the set of properties that are applied to that element.

## Syntax

Here is a example showing of a CSS rule, it is a rule applied to a p element. Pay close attention to the basic anatomy of this rule because one the common mistakes we make is forgetting to close on of the brackets, missing a semicolon, or a colon.

![CSS rule anatomy](/images/css-rule.jpg)

The selector tells which element the rule can be apply to. The declaration indicates what is going to be styled to the selected element. Property refers to the aspect of the element selected to change. Lastly the value indicates the setting chosen for that property. This seems a lot to memorize but in CSS this is repetitive, so you will encounter doing the same set of principles over and over again.

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

This is the most common way to add CSS rules to a website. It requires to have a file with extension .css named whatever you want (I would recommend a meaninful name) and a link tag from the HTML page specifying tthe css file path.

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

```css
 p {
   color: blue;
}
```