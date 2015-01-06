03 - External Files
===============

> Almost every webpage you create will have refernces to an external file. Sometimes an image, or it could be a script. 

***

### Loading an external image
> You can load an image by using the ```src``` tag. 

```html
<!-- Internal Use -->
<img src='/images/imagename.jpg'>
```

```html
<!-- external use -->
<img src='http://placehold.it/350x150'>
```

### Adding image to CSS
> You can also add images to some CSS rules.  You do this by using the `background-image:` or `background:` properties.

```css
.backgroundimage {
	background-image: url('/images/imagename.jpg');
	background-repeat: no-repeat;
}

.background {
	background: url('http://placehold.it/350x150');
	background-repeat: no-repeat;
}
```

### Adding a JavaScript to a page
> At the bottom of your page, just before you close the `<body>` tag for a page, you can link to JavaScripts. 

```html
<body>
	<p>Content of page</p>
	<!-- Linking to external and remotely hosted (CDN) scripts -->
	<script type='text/javascript' src="//code.jquery.com/ui/1.10.4/jquery-ui.js"></script>
	<!-- Linking to internal scripts -->
    <script type='text/javascript' src="/js/bootstrap-tour.min.js"></script>
</body>
```

### Adding a stylesheet to a page
> In the `<head>` tag for a page, you can link to stylesheets. 

```html
<head>
	<!-- Linking to external and remotely hosted (CDN) stylesheets -->
	<link rel="stylesheet" href="//code.jquery.com/ui/1.10.1/themes/base/jquery-ui.css" type="text/css" media="all">
	<!-- Linking to internal scripts -->
	<link rel="stylesheet" href="/css/main.css">
</head>
```
Note: Styles will be applied in the order in which they are specified on the page. The last stylesheet loaded will override any other on the page. See [What Is CSS?](syllabus/02 What is CSS.md).

***

### Summary
> You can add various types of files to a page in order to load images, create functionality and set style information.

***

### Homework 00

TBD