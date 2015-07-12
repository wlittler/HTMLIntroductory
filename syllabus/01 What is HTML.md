# HTML - HyperText Markup Language

This first week we will discover what a website consists of and how the content is structured. We will create html files, write code in them, and see how the browser interprets it.

We understand that HTML stands for HyperText Markup Language and I want to emphasize what markup means in context. In simple terms, it is a set of characters that differ from the regular text in the body of a document.

Here is an example showing an HTML tag used on website, the `<p>...</p>` element. Pay close attention to the basic anatomy of this tag because a common mistake is to forget a piece or forget to close it.

![Tag anatomy](/images/tags.jpg)

>If I write `<p This is a paragraph </p>`, you should be able to identify the error and explain that the opening tag is missing the right bracket.

If you want to dive in and see other available HTML tags and their use, please review this page on [W3Schools](http://www.w3schools.com/tags/default.asp).

## HTML5

Now that we know what a tag is, we are ready to start coding our first webpage. This course is focused on the use of HTML5. Since the `www` was invented in 1989, HTML has evolved into a more robust language with more focus on the structure of the content.

In order to have the most simple/basic semantic website we only need a few tags. Take a look at this snippet

```html
<!doctype html>
<html>
    <head>
        <title>A simple HTML 5 page</title>
    </head>
    <body>
        Content goes here.
    </body>
</html>
```
### doctype
The `<!doctype>` declaration is not an HTML tag but an instruction to the agent or web browser on what version of HTML web page is using. In this class, we will focus on the HTML5 doctype.

### html (tag)
The `<html>`tag is the container for the entire HTML code that you write. Everything between `<html>` and `</html>` is HTML code and will be displayed or used on the webpage. The html element is `<html></html>` meaning that the element consists of the opening and closing tag and whatever is between them, although you will hear some people use the words tag and element interchangeably. 

### head (tag)
The `<head>` tag is a container for all the head elements. In HTML5, it is optional but strongly recommended. Here we can link CSS files, font, and more. 

### title (tag)
The `<title>` tag will display the text on the user’s browser on the tab or window title.

### body (tag)
The `<body>` tag contains all the contents of an HTML document, such as text, hyperlinks `<a></a>`, images `<img>`, tables `<table></table>`, lists `<li></li>`, and more - it includes everything that will be displayed within the browser.

Having a knowledge of these tags will help you create a website. HTML was designed to structure the content on a page but not the style. That's why if you copy the sample code above you will get a white background and black text at the top left corner.

![Basic example](../images/basic-html-site.JPG)

<hr>

## Structure

The way a document is structured directs the flow of information. We read from left to right, top to bottom. Think of a newspaper. We can easily identify the headline, subheadings, images, and can tell one story from another. This is because of how the newspaper page is structured. Word documents work the same way. If you have ever written a paper, you can recall you had a structure including headings, subheadings and paragraphs. We do the same thing with our webpages. 

In this first week while covering HTML, we need to keep in mind of how structure is built into the code. Structure is key. You would not just want to throw a bunch of text onto a page with no heading, no subheadings, no paragraphs...it would not be easy or pleasant to read.

###Semantic structure

Before HTML5 came out, development of websites had little self-descriptive structure. The elements needed to be labeled with  an id to determine their semantic function within the page. Ex - `<div id="nav">...</div>`.

The following code depicts HTML structure prior to HTML5:

```html
<body>

  <div id="header">
    <!-- header content goes in here -->
  </div>

  <div id="nav">
    <!-- navigation menu goes in here -->
  </div>

  <div id="main">
    <!-- main page content goes in here -->
  </div>

  <div id="sidebar">
    <!-- sidebar content goes in here -->
  </div>

  <div id="footer">
    <!-- footer content goes in here -->
  </div>

</body>
```

Most websites will have a similar pattern: header, navigation, main section, sidebar, and footer. This pattern became widespread, so the guys at W3C incorporated it into their standard. There is more to HTML5 than what I am showing.

The following code demostrates how it would look using the HTML5 semantic elements. In this case you can determine what the element is without the use of any attribute making these elements have meaning by themselves.

```html
<body>
    <header>
        <!-- header content goes in here -->
    </header>
    <nav>
        <!-- nav content goes in here -->
    </nav>
    <main>
        <!-- main content goes in here -->
    </main>
    <aside>
        <!-- aside content goes in here, what it used to be sidebar -->
    </aside>
    <footer>
        <!-- footer content goes in here -->
    </footer>
</body>

```

<hr>

## Day 1 - Follow along demonstration of HTML page elements

On our first day we will create an HTML file and start adding elements, cover the normal document flow of elements, bring in outside pictures, fonts, and view the code on the browser's developer tool through a hands on exercise.

### Homework for day 1 

Visit [W3Schools](http://www.w3schools.com/html/default.asp) and go from the Introduction section through the Comments section but skip the Style section. 

Visit a few webpages and view their source by right-clicking anywhere on the page and selecting View source from the dropdown menu to get a feel for what code looks like for various pages. You will not understand all of it, but you will get a sense of how it is structured. 

Replicate website. This is skills practice and if you get stuck, don't worry, because we will go over this in the next class.

[Excercise Image](/images/Exercise-day-1.jpg)

<hr>

## Day 2 - Demo, Q & A about homework, HTML5 Semantic Elements

We will go over the homework from the first day and solve any roadblock encountered. We will talk about the new semantic elements that come with HTML5 that allow us to create a website.

### Homework for day 2

Visit [W3School](http://www.w3schools.com/html/html5_intro.asp) HTML5 section and go from the introduction through the Style Guide section.

Replicate website. This is skills practice and if you get stuck, don't worry, because we will go over this in the next class. Remember to structure it semantically and not just visually.

[Exercise Image](/images/exercise-day-2.jpg)
