###  Quiz – Precedence and Selectors

Specificity is calculated by counting what components?
> type, id, class, in-line

Name 3 CSS properties that are not inherited.
> margin, padding, border,

If two CSS rules have the same weight, and are affecting the element at the same property level, which one would win?
> The last one 

Weight the following selector

* `#mario p`
> (0,1,0,1)

* `nav.bright a:hover`
> (0,0,1,2) 

* `body aside .luigi`
> (0,0,1,2)

* `Link`
> not an actual element

* `style="color: red;"`
> (1,0,0,0)

Give an example of an attribute selector.
> `<a href="www.google.com">Link</a>`
> [href^="www"]