# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [_False_] `<div><span>hello</div></span>`

b) [_False_]

```html
<ul>
<li>one</li>All of the completed workshops need to be in your GitHub account and have an approval of one of the staff.
</ol>
```

c) [_True_] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Based on [Wikipedia](https://en.wikipedia.org/wiki/Screen_reader), screenreader converts words from text to sounds for the impaired population.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

* `<html></html>`
* `<head></head>`
* `<body></body>`
* `<img>`

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

* `<html></html>`
* `<head></head>`
* `<body></body>`
* `<p></p>` (maybe?)
* `<ul> <li></li> </ul>` 
* `<a></a>`
* `<img>` (maybe?)

c) You want to sell designer hats. You need to receive orders from the user.

* `<html></html>`
* `<head></head>`
* `<body></body>`
* `<span></span>`
* `<p></p>`
* `<img>` (maybe?)
* `<input type="text">`
* `<input type="button">`

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

Yes you can (I tested out of interest). The button will spread out as it appears normal. However I didn't test for functionality.

But you shouldn't.
Based on the documentation ([source](https://www.w3.org/TR/html51/sec-forms.html#elementdef-button)), there mustn't be any interactive contents as descendants.

And it will become confusing for anyone who wants to read the code.


## Q5 - What is the most generic tag you can use?

`<span><\span>`

## Q6 - What do the following achronyms stand for?

a) `a`  anchor tag (hyperlink)

b) `ol`  ordered list

c) `ul`  unordered list

d) `li`  list item

e) `tr`  table row

f) `th`  table header

g) `td` table cell / data

## Q7 - Usually, `td` elements are children of what kind of elements?

They should be children of table row elements.
i.e. table row (`<tr></tr>`).

## Q8 - What is the difference between td and th?

th is for table head. Defaultly the texts are bold, and the table elememt would rely on th elements to create columns.
td is for table data, and should be used by tr element to match each column defined by th.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1.

## Q10 - In which situation can you use self closing tags?

When there is no contents, and when the version of html supports it.

## Q11 - What is autofilling and why is it important?

It's when the broser autocompletes the input fild for the user. This will make filling in contents easier and more efficiently.

## Q12 - Which attributes are always present in an img element?

src

## Q13 - Which attribute is always present for an anchor tag?

href