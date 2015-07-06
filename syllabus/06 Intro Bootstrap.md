#CSS Media Queries

CSS Media Queries are a feature in CSS3 which allows you to specify when certain CSS rules should be applied. This allows you to apply a special CSS for mobile, or adjust a layout for print. 

A media query consists of a media type and at least one expression that limits the style sheets' scope by using media features, such as width or height.

Media  queries consist of a media type and can, as of the CSS3 specification, contain one or more expressions, expressed as media features, which resolve to either true or false. The result of the query is true if the media type specified in the media query matches the type of device the document is being displayed on and all expressions in the media query are true.

Here is an example:
`@media (max-width: 600px)`

Media queries can be used on a link element or within a stylesheet

```html
<!-- CSS media query on a link element -->
<link rel="stylesheet" media="(max-width: 800px)" href="my-style.css" />

<!-- CSS media query within a stylesheet -->
<style>
@media (max-width: 600px) {
  .column {
    display: none;
  }
}
</style>

```
There are different types of media such as TV, screen, or print and also the orientation of the of it (landscape or portrait). We will concentrate on screen and width (max or min).

You can find more information about it [here](http://cssmediaqueries.com/what-are-css-media-queries.html)

# Introduction to Boostrap

Bootstrap is one of the most popular frameworks for developing responsive websites. We will introduce Bootstrap this week so we can build [responsive](http://en.wikipedia.org/wiki/Responsive_web_design) sites. To be more specific, we will build our site again but this time using this framework focus on mobile first.

## Getting started

To get started, download the [zip file](https://github.com/twbs/bootstrap/releases/download/v3.3.4/bootstrap-3.3.4-dist.zip). This zip file has 3 folders: CSS, js, and fonts.

![Bootstrap folders](/images/bootstrap-folders.jpg)

Inside the CSS folder you will find six files, but we will only use `bootstrap.min.css`.

![Bootstrap minify css file](/images/bootstrap-min-css.jpg)

Inside the js folder you will find 3 files, but we will only use `bootstrap.min.js`.

![Bootstrap minify js file](/images/bootstrap-min-js.jpg)

For the fonts, we are not going to use them but if you wish to know more, visit this [page](http://getbootstrap.com/components/#glyphicons).

All you have to do is copy those files into your project's css and js folder.

![Project using bootstrap](/images/project-bootstrap.jpg)

## What we will cover in Bootstrap

Certainly there is a lot to talk about Bootstrap. It is a very extensive topic and I hope after this course you have the confidence to go back and learn the rest of the components Bootstrap has to offer. We will concentrate on learning the grid system, responsive utilities, and navigation. These three components will allow us to manipulate the elements on the website and target to different screen sizes. Bootstrap also changes the appearance of the rest of the HTML elements (e.g. h1, ul, button, etc) but we can gain the control by using a custom css file and adjusting things to our needs.

### Grid system

Bootstrap includes a responsive, mobile first fluid grid system that appropriately scales up to 12 columns according to the screen size. Grid systems are used for creating page layouts through a series of rows and columns that holds the content.

We will be making two distinctions: phone(sx) and everything above that such as tablet(sm), laptop(md) and desktops(lg). Now since we have 12 columns in our grid, we can make several combinations that add up to 12, for example:

```html
<!-- It's important to have a column combination encapsulated within a row to perform well -->
<!-- This will result in 3 columns. First one is 4 column, second 2 column, and third 6 column wide -->
<!-- The total of these columns adds up to 12 -->
<div class="row">
    <div class="col-sm-4">
        This is 4 columns wide
    </div>
    <div class="col-sm-2">
        This is 2 columns wide
    </div>
    <div class="col-sm-6">
        This is 6 columns wide
    </div>
</div>
```

Here is the result:
![Grid](/images/grid-example.jpg)

By determining the amount of columns for an specific screen size all the other screen sizes bigger that the one described will inherated that size and all the smaller size will be default to 12 column width. When you define a container element like a `div` with `class=col-sm-4`, you are setting a container 4 columns wide for small, medium, and large screen size and for extra small screen will be 12 columns wide or full width.  Dont worry if this is too complex just by reading it because we will be covering this in class.

If you wish to learn more on your own time you can go and read the documentation [here](http://getbootstrap.com/css/#grid) and bring your questions to class.

<hr>

### Responsive Utility

The use of this classes will allow us to show or hide content/elements according the device specified. For example you can set a content/element to show only on phone and be hidden when the device is bigger or showing something only for big screens and hidden for tables/phones. You can use `.visible-*` or `.hidden_*` when `*` could be xs, sm, md, or lg which represents the size of the screen.

![Available classes](/images/available-table.jpg)

### Navigation

We will be using the Bootstrap navigation menu that  allows to have links on the page. This navigation is responsive. Bootstrap website has an example but I find it a bit complex to understand and it has more than what we need in our project, so I came with a simpler version of the navigation that we will be using in our project, take a look:

```html
<nav class="navbar navbar-default navbar-fixed-top" role="navigation">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#example-navbar-collapse">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
              <a class="navbar-brand" href="#">Brand</a>
            </div>

            <!-- Collect the nav links for toggling -->
            <div class="collapse navbar-collapse" id="example-navbar-collapse">
              <ul class="nav navbar-nav">
                <li>
                    <a href="#">Link</a>
                </li>
                <li>
                    <a href="#">Link</a>
                </li>
                <li>
                    <a href="#">Link</a>
                </li>
                <li>
                    <a href="#">Link</a>
                </li>
                <li>
                    <a href="#">Link</a>
                </li>
              </ul> 
            </div><!-- /.navbar-collapse -->
          </div><!-- /.container -->
        </nav>
```
As you can see there are several contaniners and classes that bootstrap uses. Don't worry too much on understanding every single one of them, just know how it works.

<hr>

### Homework day 9

Find a layout you like and feel conrtable replicating it for your midterm project. Make sire you have your layout for three break point, mobile, tablet, and laptop. If you layout does not have it, create it according to what you might think is important to show on each break points.

### Homework day 10

TBD