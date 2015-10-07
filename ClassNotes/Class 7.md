### HTML Introductory Class - Class 7 - October 5th, 2015

###Took Quiz

1. Margin, Border, Padding, Dimensions (w/h)
2. Dimensions, Padding, Border
3. Child overflows the parent element.
4. C1 Content Block - 260px X 412px, Conatiner Block - 312px X 412px

#Class 7 - Fonts, and How to Install Them

One way to find and use fonts is to go to google.com/fonts.
Once there, find your font. Select the "Use" option.
Use a maximum of three variations of your font and no more than two different types of fonts.
Leave Latin selected.
Go to the "Standard" tab, and copy and paste that link into your code.
It goes in your header, right above your stylesheets. 

That link you just copied goes on your HTML page. It needs to go before the CSS file is going to utilize that font.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Awesome website</title>
        <!-- Font from Google Fonts -->
        <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,700'>
        <!-- CSS file that is going to utiliza that font -->
        <link rel='stylesheet' href='css/my-style.css'>
    </head>
    <body>
        <!-- HTML Elements-->
    </body>
</html>
```

This is how you'd implement that font on your CSS file

```css

/* my-style.css */

body {
    font-family: 'Open Sans', sans-serif;
}

h3 {
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
}
```

###Html Reset

In order to clear the default settings for elements from browsers, we need to reset the css.
Copy and past the following code into a new css file named something like style-reset.css:

```html
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}
```

###Basic Website Folder Setup

Typically, the cleaner and more organized you can be with your code/life, the better!

So, to make an orderly structure for your projects/excercises/websites, here's the standard setup:

FOLDER - Project1

    SUBFOLDER - css
    
        FILE - style.css
        
    SUBFOLDER - js
    
        FILE - main.js
        
    SUBFOLDER - img
        
        FILE - yakity_yak.jpg
        
    FILE - index.html
    
    
** REMBER TIME **  

The browser will read DOWN your html and css files. So the order you link and reference objects and other files is UBER important  

** END OF REMEMBER TIME **


background-size description here:  http://www.w3schools.com/cssref/css3_pr_background-size.asp

in your css, this is how to link to your image for the background image:

create an img folder within your project. then:

```html
#landing {
    background-image: url('../img/name_of_your_image.jpg');
}
```
