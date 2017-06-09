# How to create a Markdown file

Markdown is a writing tool that allows you to write plain text whilst tagging your formattings quickly

***

### Adding Code and syntax highlighting

By wrapping text in between three backquotes -- '`', not single quotations -- and a next line, you can make text appear in a box like most of my syntax examples are seen below.

If you add a language, like python, or java, or javascript, etc immediately following the first set of three backquotes, not only will the text go into its own box but it will also get highlighted according to the language you chose, as seen below

Real Example using python:

```python
def addOne(x):
    x+1
    return x
```

***

### Headings

To create headings you can put between one and six "#" before your title:

Syntax examples:

```
# My largest heading

###### My smallest heading
```

Real examples:

# Heading with one "#"

## Heading with two "#"

### Heading with three "#"

#### Heading with four "#"

##### Heading with five "#"

###### Heading with six "#"

***

### Horizontal Rule

You can add a Horizontal Rule by putting three underscores, asterisks, or minus signs together one line alone

Syntax Example:

```
___

or

---

or

***
```

Real Example:

***

***

### Phrase emphasis

You can make text italic by putting an asterisk or underscore before and after your statement

Syntax example:

```
*This would be italic if it wasn't in a code block*

_This would also be Italic because of the underscores_
```

Real Example:

Look, *this is Italic*, isn't that cool?

You can also make text bold by putting two asterisks or underscores around it

Syntax Example:

```
**This would be BOLD because this statement has two asterisks wrapped around it**

__This would be BOLD too__
```

Real example:

**BOLD TEXT**

Using a combination of underscores and asterisks you can make text bold and italic

Syntax example:

```
**Only Bold, _Bold and Italic,** Only Italic_
```

Real Example:

**Only Bold,** **_Bold and Italic,_** _Only Italic_

To put a line through text you can wrap it with two tildes

Syntax example:

```
~~This is wrong~~
```

Real Example:

~~This is wrong~~

***

### Listing items

To list items in an unordered list you can put a minus sign followed by a space in front each item you want to list. Each item should have its own individual line, as seen in my example.

Syntax example:

```

- Item One
- Item Two
- Item Three

```

Real example:

- Item One
- Item Two
- Item Three

For an ordered list you can just put them numbers with a period after in front of each item and it will automatically format the list for you

Syntax Example:

```

1. Item

2. Item

3. Item

```

Real Example:

1. Item

2. Item

3. Item


***

### Adding links to your Markdown File

Often times you will want to put links in your notes to other content.

To do this, you put the text you want to add a link to in square braces "[Click me to go to google.com]" followed by the URL in parentheses "(www.google.com)". After the URL in the parentheses you can add text to your link that will appear when a user hovers over the link by adding that message in quotations after your link like this: (google.com "This is a link to google")

Syntax example:

```
Why don't you [Click me to go to google.com](google.com "This link will take you to google")
```

Real example:

Why don't you [Click me to go to google.com](https://www.google.com/ "This link will take you to google")

***

### Tables

You can add tables to your Markdown by using hyphens and straight lines as seen below. By using colons too you can change how the text formats in the columns also seen below with the centered and right-alighed text

Syntax Example:

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

Real Example:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

***

### Block Quotes

You can put test in a Block Quote by putting a '>' at the beginning of the line, this will make that line stand out more. Using block quotes is good because it wraps text, unlike code and syntax highlighting

Syntax example:

```
> This text will appear in a block quote
```


Real Example:

> This text will appear in a block quote

***

### Adding a Youtube Video:

To add a youtube video it is best to use HTML because then you can add a border and image sizing that you would not have if you tried to add a video in pure Markdown

Syntax Example:

```
<a href="https://www.youtube.com/watch?v=6A5EpqqDOdk" target="_blank"><img src="http://img.youtube.com/vi/6A5EpqqDOdk/0.jpg" alt="A link to the Markdown Tutorial Video" width="240" height="180" border="10" /></a>
```

Real Example:

<a href="https://www.youtube.com/watch?v=6A5EpqqDOdk" target="_blank"><img src="http://img.youtube.com/vi/6A5EpqqDOdk/0.jpg" alt="A like to the Markdown Tutorial Video" width="240" height="180" border="10" /></a>

***

### Inline HTML

You can also add raw HTML into your Markdown and it will work most of the time, as seen above with the Youtube video

***

### Adding Images

You can add an image by using this syntax:

```
![alt tag](https://github.com/CodyNicholson/CodyNicholson.github.io/blob/master/images/topBanner.jpg)
```

With a link to your image passed as the parameter

Real Example:

![alt tag](https://github.com/CodyNicholson/CodyNicholson.github.io/blob/master/images/topBanner.jpg)
