###Class 8 - HTML Introduction - October 7th, 2015

##Quiz Answers

1. False. You don't HAVE to follow the preferences
2. CSS code is consistent to be able to read it, easier for editing, easier for other users, speed up naming
3. Comment your CSS in order to keep it organized and ease other users' passage through it
4. Code compilers.
5. em is a relational size to the default pixel size.
6. ALWAYS prioritize structure.
7. Serif, Sans-serif, Monospace
8. 
```html
a {
  font-family: 'Roboto', monospace;
}
```

##Discussing the Homework

The following code was used for the gradient with a background image:

```html
#landing {
  linear-gradient(to bottom, rgba(20,20,20,.9) 0%, rgba(0,0,0,.8) 100%), url('../img/wine.jpg') no-repeat center;
}
```

*** EARLY REMEMBER TIME ***
Any time you have a container with floating items, remember to apply the clear-fix class we made (it contains several lines of css including "clear: both")
*** END EARLY REMEMBER TIME ***

In your css, when using a background image, use "../" to jump out of your cuurent folder.

When using the shorthand property the order of the property values is:

background-color
background-image
background-repeat
background-attachment
background-position

It does not matter if one of the property values is missing, as long as the ones that are present are in this order.

