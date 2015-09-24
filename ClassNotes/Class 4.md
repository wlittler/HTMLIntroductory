# Class 4 - 9/23/2015

### Quiz
1. Inline styling and embedded style.
2. External Stylesheets
3. External Stylesheets are ALWAYS better
4. Change the text (font-size, color, line-height, letter-spacing)
5. No (different browsers have different inherit styling and interpretations)
6. HTML structures, CSS defines the look
7. px, em, rem, pc, pt, %

Went over homework. The answers are posted on the github.

How to link your stylesheet:
```html
<!DOCTYPE html>
<html>
<head>
<title><title>

<link rel="stylesheet" href="between these quotes, you will put the path to your css file" />

</head>
</html>
```

*REMINDER TIME*
  ALWAYS be case sensitive when referencing anything  
*END OF REMINDER TIME*

Selectors are inside your css file, and they are how you tell your html file which elements you want to change.

Selectors can be:

* type selectors - entire elements like a, p, div, section
    *  ( p will reference all p elements in your html file )
* ID selectors - changes an element with an attribute of that unique name 
```html 
    *  #my_id will reference <p id="my_id">This element only</p>
```
* class selectors - changes all elements with attributes of that class name 
```html 
    *  .my_container will reference <div class="my_container>This changes</div><div class="my_container">So does this!</div> 
```

The main difference between class and id selectors is that we can have multiple elements with the same class.
We DO NOT want multiple elements to have the same ID.

Inheritance is the set of properties your browser sets as default OR the set of properties you give the elements or "children" inside of a container or "parent" element.

When computing the specificity of a selector, remember:
* type selectors get you 0,0,0,1
* class selectors get you 0,0,1,0
* id selectors get you 0,1,0,0
* inline stylings get you 1,0,0,0

You can add these up for any specific element to see which rule will override other rules.
The more specific rule will always take precedence of more general rules.

### Descendant Selector
Example:
```html
body a {
   font-size: 20px;
}
```
this will select every anchor element within our body and give it a font-size of 20px. 

