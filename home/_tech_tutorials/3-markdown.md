---
layout: article
title: Markdown Starter Worksheet
permalink: /tech_tutorials/Markdown
key: Markdown
tags: Markdown
cover: assets/images/tutorial covers/markdown.PNG
---

The main goal of Markdown is to be easily written and easily read.  It uses "plain text" formatting and can be converted to HTML.  The most common use case I've come across to use Markdown is for ReadMe files, used, for example, for Github repos.  Markdown can also be used to create email.

Markdown, in comparison to HTML, is much simpler to read and write.  The average person can typically understand markdown and would be able to learn and write it much quicker than HTML.

Specifically, Visual Studio Code uses the [CommonMark](http://commonmark.org/) Markdown specification.

## Sections

Sections are defined in the code block below which when clicked takes you to that section of the document:

```markdown
[Section](#headers)
```

Here are the Sections for this page which goes through markdown's basic syntax:

- [Headers](#headers)
- [Quotes](#quotes)
- [Emphasis](#emphasis)
- [Horizontal Rule](#horizontal-rule)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Code](#code)
- [Tables](#tables)
- [Custom HTML](#custom-html)
- [Custom CSS](#custom-css)
- [Additional Resources](#additional-resources)

---

## Headers

Headers are defined by the '#'symbol.  One '#' for H1, two for H2, etc.

**Code Block Example:**
```Markdown
# Header 1

## Header 2

### Header 3

#### Header 4
```

---

## Quotes

Quotes are defined by the  '>' symbol

```markdown
>This is a qutoe yaaa yeet
```

You can also have a Header Quote using '> #'

```markdown
> # This is a Header Quote
```

---

## Emphasis

Add **emphasis** with asterisks '*' and underscores '_'
Two before and after (no spaces) a section of texts

```markdown
**Bold Text with asterisks**
    OR
__Bold Text with underscores__
```

To *italicized* text use either '*' or '_', once before and after

```markdown
 *Italicized Text with asterisks*
    OR
 _Italicized Text with underscores_
```

You can do **both** in *line*.

```markdown
This text is **bold** and this text is *italicized*
```

---

## Horizontal Rule

A horizontal rule gives a visible line break.  You can create one by putting three or more hypens, asterisks, or underscores (-, *, _).

Use one to keep consistent. I've used dashes on this page.

```markdown
---
```

---

## Lists

Create unordered lists using '-', '*', '+,

```markdown
- Text
- Text
- Text
```

The code block above looks like this:

- Text
- Text
- Text

---

## Links

Create a link by surrounding it with angle bracket '<>'

```markdown
<https://www.google.com>
```

Create a link with text by surrounding text with brackets, [], and link immediately following with parenthesis (). You will only see the text in the square brackets.

```markdown
[Google](https://www.google.com)
```

Whih looks like this: [Google](https://www.google.com)

What if you needed to reuse a link several times?  Well, you could copy and paste that link each time.  That means, if you need to update the link, you will have to do it each time its used.  There's a better way!

Create reference style links by defining your link with the a 'key' inside of brackets, colon, space, and the link.

Then use the reference style link by using your text inside of brackets followed by the link 'key' inside of bracket.

[1]: https://github.com/drkOluhv
[My Github][1]

You can also link to other locations on your markdown page.  Remember, your MarkDown will get converted to HTML, so you can, in theory, use a anchor tag to link to an element with a specific ID.  You can find an example of this in the list of sections at the top of this document.

When we create a header tag for example, it implicitly creates an id property.

Ex '# Header' becomes `<h1 id="header">Header</h1>`

Names will be converted to ids by replacing spaces with hyphens and uppercase letters with lowercase letters (think css naming convention).

Ex 'Header Info' becomes header-info

---

## Images

Defining an image is similar to defining a link, except you prefix it with '!'

![Image](https://images.unsplash.com/photo-1579159278991-f698b0667a16?q=80&w=2680&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

---

## Code

You can do inline code with 2 backticks ``backticks``
You can do blocks of code by surroung it with 3 backticks

You can specify the programming language immediately following the opening 3 backticks.  You Should see a difference in highliting!

Example Javascript

```javascript
var num = 0;
var num2 = 0;
```

Example HTML

```html
<div>
    <p>This is an html example</p>
</div>
```

Example Python

```python
layout =[   
    [sg.Text("hello from PySumpleGUI")],
    [sg.Button("OK")]
]
```

---

## Tables

Tables are useful for displaying rows and columns of data.  Column headers can be defined in between pipes (|).  Headers are separated from table content with a row of dashes (-) (still separated by pipes), and there must be at least 3 dashes between each header.  The row data follows beneath (still separated by pipes).

| Header 1    | Header 2    | Header 3    |
| ----------- | ----------- | ----------- |
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |

The column definitions and row definitions do not have to have the exact same width sizes, but it would be much more readable.

| Header 1 | Header 2 |
| ----------------| --|
|Loooooooooooooong item 1 | looooooooooong item 2 |

| Header 1                | Header 2              |
| ----------------------- | --------------------- |
|Loooooooooooooong item 1 | looooooooooong item 2 |

You can also align (Center, left, right) the text in a column by using colons (:) in the line breaks between headers and rows.  No colon means the default **left alignment**.  Colons on each side signifies **center alignment**.  And a trailing colon means **right alignment**.

Example

| Header | Header 1 | Header 2  |
| ------ | :------: | --------: |
| Aligned Left | Aligned Center | Aligned Right |

---

## Custom HTML

Since MarkDown gets automatically converted to HTML, you can add raw HTML directly to your MarkDown.

```html
<p>Sample HTML Div</p>
```

Creates this

<p>Sample HTML Div</p>
---

## Custom CSS

You can also add custom CSS to your MarkDown to add additional styling to your document. You can also include CSS by including a style tag.

```html
    <style>
        body {
            color:red;
        }
    </style>
```

<style>Custom CSS</style>

---

## Additional Resources

- [MarkDown in Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown)

© 2022 GitHub, Inc.
