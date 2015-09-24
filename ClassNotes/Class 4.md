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
	| * ( p will reference all p elements in your html file )
* ID selectors - changes an element with an attribute of that unique name 
	| * ( #my_id will reference <p id="my_id">This element only</p> )
* class selectors - changes all elements with attributes of that class name 
	| * ( .my_container will reference <div class="my_container>This changes</div><div class="my_container">So does this!</div> )

the main difference between class and id selectors is that we can have multiple elements with the same class;
we DO NOT want multiple elements to have the same ID.

