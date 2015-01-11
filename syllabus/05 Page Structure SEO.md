05 - Page Structure & SEO / Social Media
===============

> Search Engine Optimization (SEO) is the process of optimizing your website pages (code & content) in order to affect your organic page ranking with the major search engines. The way pages are built can positively or negatively affect search engine optimization so it is an important consideration.

***

### Meta & Title Tags
> Inside the ```<head>``` of the page, there are a number of optional tags you can add to dictate what search engines capture about your page. 

```html
	<head>
	<title>Up to 70 Characters of Keyword-relevant text here</title>
	<meta name=”description” content=”155 characters of message matching text with a call to action goes here”>
	<link rel=”author” href=”https://plus.google.com/[YOUR PERSONAL G+ PROFILE HERE]“/>

	</head>
```

### 508 Compliance 
> The government standards on websites to meet the Americans With Disabilities Act falls under 508 compliance. To be compliant, you have to make your site accessible and readable by screen readers. There are a number of items you can do to increase this accessibility. These should be done as a matter of best practice. 

**alt**<br>
Your alt property should never be empty. There should be an alt (alternate) property on every image tag.

```
<img alt="Readable description of image" src="/images/image.jpg">
```

**title**<br>
Your title property should never be empty. There should be a title property on every image tag.

```
<img title="Readable description of image" src="/images/image.jpg">
```

### Social Media : OpenGraph or og tags
> These meta content tags will be read by Facebook and other sites when your content is shared. They are presented as the summary of your page or article allowing you greater control over how your article is displayed on those sites. 

**og: title**
<br>
```
<meta property=”og:title” content=”Title that Facebook and other social sites will pull when shared.”/>
```
**og: type**
<br>
```
<meta property=”og:type” content=”article”/>
```
**og: image**
<br>
```
<meta property=”og:image” content=”http://www.iacquire.com/some-thumbnail.jpg”/>
```
**og: url**
<br>
```
<meta property=”og:url” content=”http://www.yourwebsite.com”/>
```
**og: description**
<br>
```
<meta property=”og:description” content=”Stop hitting refresh on your ex-girlfriend’s Facebook page? You should check out the iAcquire blog and learn something instead”/>
```

#### Social Media : Twitter Cards
> Although OG tags have the highest adoption of all content meta, Twitter has developed their own. They are presented as the summary of your page or article allowing you greater control over how your article is displayed on Twitter. 

**twitter:card**
<br>
```
<meta name=”twitter:card” content=”summary”>
```
**twitter:url**
<br>
```
<meta name=”twitter:url” content=”http://www.somedomain.com/url”>
```
**twitter:title**
<br>
```
<meta name=”twitter:title” content=”The title of the article that will display on Twitter.”>
```
**twitter:description**
<br>
```
<meta name=”twitter:description” content=”This is the description that twitter will capture for the post.”>
```
**twitter:image**
<br>
```
<meta name=”twitter:image” content=”http://www.somedomain.com/image.jpg”>
```

***

### Summary
> Everything on a page should be checked against SEO best practices. Use various tools to analyze pages to ensure proper SEO structure. During this week, we will learn many of these best practices and understand how SEO is affected by page development and other factors. 

### Links
[18 Meta tags every page should have](http://www.iacquire.com/blog/18-meta-tags-every-webpage-should-have-in-2013)

***

### Homework 00

TBD