# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [FALSE ] `<div><span>hello</div></span>`

`<div><span>hello</span></div>`

b) [FALSE ]

```html
<ul>
<li>one</li>
</ol>
```

```html
<ul>
    <li>one</li>
</ol>
```


c) [FALSE ] `<ul></ul><img/><ol><li>one</li></ol>`

```html
<ul>
    <li>
        <ol>
        <img/>
          <li>one</li>
        </ol>
    <li>
<ul>
```

## Q2 - What is a screenreader and why should we care about them?

As discussed in todays lecture and from my own prior knowledge - screenreader is a software or type of technology that helps people who are visually impaired via turning text and visual imagery into speech. That is why it is essential to keep code neat - so it can be translted well - accessability.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
I would use the following tags:
    <hi>, <h2>, <h3>, <p>, <img>, 

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
 I would use the following tags:
    <hi>, <h2>, <h3>, <p>, <img>, <button>, <ol>, <ul>, <li> <a>- i guess if you also wanted your site to be organized you could use the table elements too <tr><td><th>

c) You want to sell designer hats. You need to receive orders from the user.
I would use the following tags:
    <Img><form><input>hi><h2><h3><p><button>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
    No a button cannot be a child of a button because its children or descendants must not be clickable elements. Also i am pretty sure inline elements cannot contain other inlines.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` - anchor tag

b) `ol` - ordered list

c) `ul` - unordered list (bullet points)

d) `li` - list item

e) `tr` - table row

f) `th` - table head

g) `td`- table data

## Q7 - Usually, `td` elements are children of what kind of elements?

Child of a tr element - table row

## Q8 - What is the difference between td and th?

The difference between them is that one is the table head and holds the title for the table whereas td is table data and holds the data for it.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

hi as it is usually the tag for the page title whereas h3 is a tag for subsections.

## Q10 - In which situation can you use self closing tags?

You can use self closing tags if the element you are working on does not have children

## Q11 - What is autofilling and why is it important?

## Q12 - Which attributes are always present in an img element?

## Q13 - Which attribute is always present for an anchor tag?
