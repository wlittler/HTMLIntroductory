01 - What is CSS?
===============

> CSS stands for Cascading Style Sheets. HTML was never intended to control the formatting of the items on the page, that is why CSS was created. CSS controls both formatting and position of elements on an HTML page.

***

### Syntax
> There are 3 ways to add CSS to your page. Page Reference, External stylesheets and inline. For best practices, you should never use inline styles.  

```html
<!-- Page Reference -->
<sytle>
.element {
    font-weight: bold;
    font-size: 1em;
    padding: 10px 15px 3px 15px;
}
</sytle>

<!-- External stylesheet reference -->
<link href="/css/style.css" rel="stylesheet">

<!-- Inline Styles -->
<div style="font-weight:bold">This content will be bold.</div>
```
> Standard CSS has 2 available declarations. Classes and ID tags. 

#### Targeting an element with a class
> Classes should be used on elements that need positioning or visual formatting. Classes are NOT unique.
> You can use the same class on multiple elements.
> You can use multiple classes on the same element.

```css
/* Class */
/* Periods are used to note classes. */
.element {
    
}
```

```html
<div class="element"></div>
```

#### Targeting an element with an ID
> Each element can have only one ID
> Each page can have only one element with that ID
> IDs are unique.

```css
/* ID */
/* Pound signs are used to note IDs. */
#element {
    
}
```

```html
<div id="element"></div>
```

#### The use of comments
> Comments are used to make notes in a css document. These are not visible to the user, but are visible when reading the page source. 

```css
/* This is a CSS comment */
```

***

### Summary
> In ac felis quis tortor malesuada pretium. Praesent metus tellus, elementum eu, semper a, adipiscing nec, purus. Ut leo. Curabitur nisi. Fusce risus nisl, viverra et, tempor et, pretium in, sapien.

[CSS Propery References](http://www.w3schools.com/css/css_intro.asp)

***

### Homework 02 

TBD