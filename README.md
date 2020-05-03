# Markdown Cheatsheet

## What is Markdwon ?

Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor. [click here more info](https://en.wikipedia.org/wiki/Markdown)

## Table of Content



**[Headers](#Headers)**

**[Bold](#Bold)**

**[Emphasis](#Emphasis)**

**[Strikethrough](#Strikethrough)**

**[Lists](#Lists)**

**[Links](#Links)**

**[Images](#Images)**

**[Code Block](#Code-Block)**

**[Table](#Table)**

**[Blockquotes](#Blockquotes)**

**[Horizontal Rule](#Horizontal-Rule)**

**[HTML into Markdown](#HTML-into-Markdown)**

**[Markdown into HTML](#Markdown-into-HTML)**

---

# Headers

Code:

```markdown
# h1

## h2

### h3

#### h4

##### h5

###### h6
```

Output:

# h1

## h2

### h3

#### h4

##### h5

###### h6

# Paragraph

Code:

```markdown
i am paragraph.
do not take saparate paragraph

take new line for separate paragraph
```

Output:

i am paragraph.
do not take saparate paragraph

take new line for separate paragraph

[back to top](#Table-of-Content)

# Bold

```markdown
i am **Bold**
```

Output:

i am **bold**

[back to top](#Table-of-Content)

# Emphasis

Code:

```markdown
i am *emphasis*

or

i am _emphasis_
```

Output:

i am *Emphasis*

or

i am _Emphasis_

[back to top](#Table-of-Content)

# Strikethrough

```markdown
i am ~~Strikethrough~~
```

Output:

i am ~~Strikethrough~~

[back to top](#Table-of-Content)

# Lists

## Unordered Lists

Code:

```markdown
- i am unorderd list
- i am unorderd list
- i am unorderd list
```

Output:

- i am unorderd list
- i am unorderd list
- i am unorderd list

## Nested Unorderd Lists

Code:

```markdown
- i am unorderd list
  - i am nested unorderd list
  - i am nested unorderd list
- i am unorderd list
- i am unorderd list
```

Output:

- i am unorderd list
  - i am nested unorderd list
  - i am nested unorderd list
- i am unorderd list
- i am unorderd list

Note: you can also use \* or +

## Orderd List

Code:

```markdown
1. i am orderd list
1. i am orderd list
1. i am orderd list
```

Output:

1. i am orderd list
1. i am orderd list
1. i am orderd list

## Nested Orderd List

Code:

```markdown
1. i am orderd list
   1. i am orderd list
   1. i am orderd list
1. i am orderd list
1. i am orderd list
```

Output:

1. i am orderd list
   1. i am orderd list
   1. i am orderd list
1. i am orderd list
1. i am orderd list

[back to top](#Table-of-Content)

# Links

Code:

```markdown
i am inline link

<https://www.google.com/>

i am link with title and tooltip

[google.com](https://www.google.com/, "this is tooltip")

i am link without title and tooltip

[google.com](https://www.google.com/)

i am link use reference

[google.com][1]

[youtube.com][youtube]

[1]: https://www.google.com
[youtube]: https://www.youtube.com/
```

OutPut:

i am inline link

https://www.google.com

or

<https://www.google.com>

i am link with title and tooltip

[this is title](https://www.google.com/, "this is tooltip")

i am link without title and tooltip

[this is title](https://www.google.com/)

i am link use reference

[this is title][this is reference]

i am link use number reference

[this is title][1]

[this is reference]: https://www.youtube.com/
[1]: https://www.google.com

[back to top](#Table-of-Content)

# Images

Code:

```markdown
![this is image alt txt](https://source.unsplash.com/random/200x150)

![this is image alt txt][thisisreference]

image use into link and reference big image

[![this is small image][smallimage]][fullimage]

[thisisreference]: https://source.unsplash.com/random/250x150
[smallimage]: https://source.unsplash.com/random/30x30
[fullimage]: https://source.unsplash.com/random/500x500
```

Output:

![this is image alt txt](https://source.unsplash.com/random/200x150)

![this is image alt txt][thisisreference]

image use into link and reference big image

[![this is small image][smallimage]][fullimage]

[thisisreference]: https://source.unsplash.com/random/250x150
[smallimage]: https://source.unsplash.com/random/30x30
[fullimage]: https://source.unsplash.com/random/500x500

[back to top](#Table-of-Content)

# Code Block

Code:

<pre>
```javascript
var javaScript = "javascript txt highlight";
console.log(javaScript);
```

```
  var javaScript = "you don't select language, so no syntex highlight";
  console.log(javaScript);
```
inline code `var x = "inline code";`

</pre>

Output:

```javascript
var javaScript = "javascript txt highlight";
console.log(javaScript);
```

```
  var javaScript = "you don't select language, so no syntex highlight";
  console.log(javaScript);
```

inline code `var x = "inline code";`

[back to top](#Table-of-Content)

# Table

Code:

```markdown
| heading1   |   heading2   |    heading3 |
| :--------- | :----------: | ----------: |
| align left | align center | align right |
| align left | align center | align right |
```

Output:

| heading1   |   heading2   |    heading3 |
| :--------- | :----------: | ----------: |
| align left | align center | align right |
| align left | align center | align right |

[back to top](#Table-of-Content)

# Blockquotes

Code:

```markdown
> i am blockquote

> blockqoute separate new line

> Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.
```

Output:

> i am blockquote

> blockqoute separate new line

> Markdown is a lightweight markup language with plain-text-formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

[back to top](#Table-of-Content)

# Horizontal Rule

Code:

```markdown
use \*\*\* or --- or \_\_\_ three time or more then three time

use new line before Hyphens

---

Asterisks

***

Underscores

___
```

Output:

use \*\*\* or --- or \_\_\_ three time or more then three time

use new line before Hyphens

---

Asterisks

***

Underscores

___

[back to top](#Table-of-Content)

# HTML into Markdown

Code:

```markdown
you can use HTML into markdown

[<img src="https://source.unsplash.com/random/50x50">](https://source.unsplash.com/random/500x500)
```

Output:

you can use HTML into markdown

[<img src="https://source.unsplash.com/random/50x50">](https://source.unsplash.com/random/500x500)

[back to top](#Table-of-Content)

# Markdown into HTML

Code:

```markdown
  <p>you can not use *Markdown* into **HTML** <p>
```

Output:

<p>you can not use *Markdown* into **HTML** <p>

[back to top](#Table-of-Content)
