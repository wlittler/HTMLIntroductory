04 - Images, Backgrounds and Formatting
===============

> For this lesson, we will turn our attention to working with images. We will also go through various techniques in CSS for backgrounds and formatting of page content. Some of the items we touch on will help to format and position content. 

***

### Image styles
> Images can have styles applied to them like any other element. Stay away from inline styles and use classes to apply formatting to images. 

```html
<style>
/* This will apply a 2px solid grey border to the image and round the corners of the image */
.image {
	border: 2px solid #e2e2e2;
	border-radius: 8px;
}
</style>
<body>
<img class="image" src="/images/imagename.jpg" alt="Image Text onMouseover.">
</body>
```

### Using an image as a background
> Images can also be used as the background of an element. Using them as backgrounds can give you greater control over its formatting. It keeps your code lean.

```html
<style>
/* This will set the background image, apply a 2px solid grey border and round the corners. */
.image {
	border: 2px solid #e2e2e2;
	border-radius: 8px;
	background-image: url('/images/imagename.jpg');
	background-repeat: no-repeat;
	width: 300px;
	height: 100px;
}
</style>
<body>
<div class="image">
</body>
```

### CSS Background properties
CSS background properties are used to define the background effects of an element.<br>
CSS properties used for background effects:
  <ul>
	  <li>background-color</li>
	  <li>background-image</li>
	  <li>background-repeat</li>
	  <li>background-attachment</li>
	  <li>background-position</li>
  </ul>

**background-color**
> The background-color property specifies the background color of an element.

```css
h1 {
    background-color: #ff0000;
}
p {
    background-color: rgb(255,0,0);
}
.redbackground {
    background-color: "red";
}
```

**background-image**
> The background-image property specifies an image to use as the background of an element.

```css
body {
    background-image: url("/images/imagename.jpg");
}
```

**background-repeat**
> The background-repeat property specifies if and how the image in the background will repeat. Default: "repeat"<br>
It can repeat the following ways:<br>
<ul>
	<li>background-repeat: repeat | repeat-x | repeat-y | no-repeat | initial | inherit;</li>
</ul>

```css
body {
    background-image: url("/images/imagename.jpg");
    background-repeat: repeat-x;
}
```

**background-attachment**
> The background-attachment property sets whether a background image is fixed or scrolls with the rest of the page. Default: "fixed".
<ul>
	<li>background-attachment: scroll | fixed | local | initial | inherit;</li>
</ul>

```css
body {
    background-attachment: fixed;
}
```

**background-position**
> The background-image property specifies an image to use as the background of an element.

```css
body {
    background-image: url("/images/imagename.jpg");
    background-position: top left;
}
```
***

### Summary
> The formatting of images and backgrounds is a fundamental piece of HTML development. Learning the how to bend backgrounds and images to your will gives you flexibility in all your development projects. 

***

### Homework 04

TBD