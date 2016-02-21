###  Quiz - Float and Clear

Name the four values that we can apply to floats.

What is the normal behavior of block-level elements? - in terms of presentation

How do we call to that behavoir in class?

What do call in class when a `container element` that contains any number of floated elements doesn’t expand to completely - or it shrink?

What would be the main reason for us to use float on elements?

Given the following code:

```html
<style>

	.container {
		width: 250px;
		height: 150px;
		float: left;
	}

	/*More CSS rules in between*/

	section article {
		float: none;
		background-color: #ccc;
	}
</style>

<section>
	<article class="container">
		<img src="img/article1.jpg" alt="earth"/>
		<p>The Earth is the 3rd planet in our solar system. Full of life and intelligent life capable of inventing the selfy stick</p>
	</article>
	<article class="container">
		<img src="img/article2.jpg" alt="mars"/>
		<p>Mars is believe to have saled water. The reason we haven't gone there yet its because we haven't found oil.</p>
	</article>
</section
```

Is the element `article` floating?