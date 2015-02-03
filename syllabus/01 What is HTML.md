01 - What is HTML?
===============

> HTML stands for *HyperText Markup Language*. HTML is the computer language used to build the structure of a web page. HTML gives you the power to add text and images to a web page. 

***

### HTML Page Syntax (HTML5)

```html
<!DOCTYPE html> 
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    The page content goes here.
</body>
</html>
```

#### Doctype
> The ```<!DOCTYPE>``` declaration is not an HTML tag but an instruction to the web browser about what version of HTML the page is. For this class, we will focus on the HTML5 doctype.

```html
<!DOCTYPE html>
```

#### head (tag)
> The ```<head>``` element is a container for all the head elements. In HTML5, it is optional but strongly recommended.

```html
<head></head>
```

#### body (tag)
> The ```<body>``` element contains all the contents of an HTML document, such as text, hyperlinks ```<a></a>```, images ```<img>```, tables ```<table></table>```, lists ```<li></li>```, etc.

```html
<body></body>
```

#### Making words or lines bold.
> The preferred way of making content bold.

```html
<strong>This whole line of text will be bold.</strong>

Only the word <strong>bold</strong> is emphasized.
```

#### Making words or lines bold (alternate method).
> The ```<b>``` tag can also be used to bold an item.

```html
<b>This whole line of text will be bold.</b>

Only the word <b>bold</b> is emphasized.
```

Note: Use ```<strong>``` when you want to emphasize the content and bold the term(s). Use ```<b>``` when you just want it bold but stressing the content is unnecessary.

#### Making words or lines italicized.
> Italics can be used where necessary.

```html
<i>This whole line of text will be in italics.</i>

Only the word <i>italics</i> is in italics.
```

#### Adding a hard return to a line (line break).
> When you dont need a paragraph but still need a line break, use the ```<br>``` tag.

```html
You can take a line of text and <br> break it anywhere.

```

#### Adding paragraphs
> If you need structured paragraphs, you can use the ```<p>``` tag. 

```
<p>This is the content that will display as a paragraph. You can add as many sentences as you need.</p>

<p>You can also have as many paragraphs as necessary.</p>
```

#### The use of comments
> Comments are used to make notes in a page. These are not visible to the user, but are visible when reading the page source. 

```html
<!-- This is an HTML comment -->
```

### Summary
> If you do prep work, or know a little about HTML week 1 will be a time to brush up on those skills. More importantly, a time to ask questions about "why" you do certain things. The "why" is almost as important as the "how".

### Code example

[http://codepen.io/jsteinmetz/pen/MYEEja.html](http://codepen.io/jsteinmetz/pen/MYEEja.html)

### Homework 01 

1. Lookup the CSS boxmodel - learn about it.
2. Install MAMP (or any other local web server)
3. Install Sublime (or any other code editor program)
4. Look over CSS properties at w3schools.com
5. Browse at least 1 well known website and 1 very unknown website. On each of those sites right click and view the page source. When you see the code, look at everything in the <head></head> area. We will discuss. 