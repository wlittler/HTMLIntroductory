#CSS Media Queries

CSS Media Queries are a feature in CSS3 which allows you to specify when certain CSS rules should be applied. This allows you to apply a special CSS for mobile or adjust a layout for print. 

A media query consists of a media type and at least one expression that limits the style sheets' scope by using media features, such as width or height.

Media  queries consist of a media type and can contain one or more expressions, expressed as media features, which resolve to either true or false. The result of the query is true if the media type specified in the media query matches the type of device the document is being displayed on and all expressions in the media query are true.

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
There are different types of media such as TV, screen, or print and also the orientation of the of it (as in landscape or portrait). We will concentrate on "screen" and "width" (max or min).

You can find more information about it [here](http://cssmediaqueries.com/what-are-css-media-queries.html)

# GitHub and GitHub App

So far we have worked on individual projects where one person makes all the changes to the files and those files have no history. Once you save those files there isn't a way to go back to something like a checkpoint. And working by yourself you generally do not have other web developers working on the same project or file.

To solve this problem there is a technology called [Git](https://en.wikipedia.org/wiki/Git_(software)) and a website [GitHub][http://www.github.com] that allows people to collaborate on projects. Projects are stored in [repositories](https://en.wikipedia.org/wiki/Repository_(revision_control)). People get access to them by being added as collaborators for that repository. This allows for cloning of the repository and also for collaborators to modify files and upload those changes onto the repository.

I invite you to create an account on GitHub and download the GitHub App for [Mac](https://mac.github.com/) and [Windows](https://windows.github.com/). During class we will create our first repository, clone it to our computer, add a file, and upload those changes (also called push changes).

If you wish to know more visit [GitHub Training](https://training.github.com/classes/) to get more information and training.

##CSS Media Queries Homework

This [image](https://github.com/AustinCodingAcademy/HTMLIntroductory/blob/master/exercises/week-6/media-query.jpg) has the layout I want you to replicate using Media Queries

You can either use three different files and add the media query to the link tag like this:
```html
<!-- This goes within your html file right below the title element-->

<link rel="stylesheet" media="(min-width: 993px)" href="css/latptop-layout.css"/> 

<link rel="stylesheet" media="(max-width: 992px) and (min-width:769px)" href="css/tablet-layout.css"/>

<link rel="stylesheet" media="(max-width: 768)" href="css/phone-layout.css"/>

```

Or you can create a single CSS file and add the media queries on it, like this:

```CCS

@media screen and (min-width: 993px) {

    /*Write CSS rules for Laptop layout*/
}

@media screen and (max-width: 992px) and (min-width:769px) {

    /*Write CSS rules for Tablet layout*/
}

@media screen and (max-width: 768) {

    /*Write CSS rules for Phone layout*/
}

```


###GitHub Homework

During class, you will partner up and one of you will create a repository, invite the other classmate to be a collaborator and both clone the repository on your laptop and start working together to replicate this [simple exercise](https://github.com/AustinCodingAcademy/HTMLIntroductory/blob/master/exercises/week-6/simple-exercise.JPG).

As homework for the weekend there is another layout you will have to do with a partner and using a GitHub repository. You have to do only two layouts, one for [laptop](https://github.com/AustinCodingAcademy/HTMLIntroductory/blob/master/exercises/week-6/laptop.png) and one for [phone](https://github.com/AustinCodingAcademy/HTMLIntroductory/blob/master/exercises/week-6/phone.png).
