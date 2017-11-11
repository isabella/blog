---
title: "Markdown Tutorial"
slug: markdown-tutorial
date: 2016-01-23
---

This tutorial is an overview of markdown editing for this site.

<!-- excerpt -->

## Table of Contents
[Text](#text)
[Headers](#headers)
[Emphasis](#emphasis)
[Lists](#lists)
[Links](#links)
[Images](#images)
[Code](#code)
[Tables](#tables)
[Blockquotes](#blockquotes)
[Emoji](#emoji)
[Math](#math)

## Text

```
Text is just text.
Separate paragraphs with an empty line.

Like this.
```

Text is just text.
Separate paragraphs with an empty line.

Like this.

## Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

```
Italic with *asterisks*.
Bold with **double asterisks**.
Underline with _underscores_.
Strikethrough with ~~tildes~~.
```

Italic with *asterisks*.
Bold with **double asterisks**.
Underline with _underscores_.
Strikethrough with ~~tildes~~.

## Lists

```
Ordered lists start with numbers followed by a period.
Unordered lists start with an asterisk, minus, or plus, your choice.
Indent sublists by at least one space.

1. Ordered List Item 1
   1. ordered sublist item 1
   2. ordered sublist item 2
2. Ordered List Item 2
   - unordered sublist item 1
   - unordered sublist item 2

* Unordered List Item 1
* Unordered List Item 1
```

Ordered lists start with numbers followed by a period.
Unordered lists start with an asterisk, minus, or plus, your choice.
Indent sublists by at least one space.

1. Ordered List Item 1
   1. ordered sublist item 1
   2. ordered sublist item 2
2. Ordered List Item 2
   - unordered sublist item 1
   - unordered sublist item 2

* Unordered List Item 1
* Unordered List Item 1

## Links

```
Here's some tex with a [link](https://www.google.com).

Here's some tex with a [link](https://www.google.com "Google's Homepage") with a title.

Here's a [reference link][ArbiTrarY CasE-InsenSitive ReferencE TexT]

Here's one with just the [link reference text itself].

URLs will automatically get turned into links.
http://www.example.com or <http://www.example.com>.

Some filler text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[link reference text itself]: http://www.reddit.com
```

Here's some tex with a [link](https://www.google.com).

Here's some tex with a [link](https://www.google.com "Google's Homepage") with a title.

Here's a [reference link][ArbiTrarY CasE-InsenSitive ReferencE TexT]

Here's one with just the [link reference text itself].

URLs will automatically get turned into links.
http://www.example.com or <http://www.example.com>.

Some filler text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[link reference text itself]: http://www.reddit.com

## Images

```
![alt text](https://placehold.it/250x100)

![alt text][logo]
[logo]: https://placehold.it/250x100
```

![alt text](https://placehold.it/250x100)

![alt text][logo]
[logo]: https://placehold.it/250x100

## Code

```
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

Blocks of code are fenced by lines with three back-ticks <code>```</code> and optionally specify the language.

<pre lang=""><code>```javascript
var s = "JavaScript syntax highlighting";
```
</code></pre>

```javascript
var s = "JavaScript syntax highlighting";
```

## Tables

```
Make tables by using pipes to separate columns.

Tables | Are | Cool
--- | --- | ---
1 | 2 | 3

Make your table pretty if you want with whitespace and colons to align columns.

| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 1 left    | 1             | A     |
| col 2 center  | 2             | B     |
| col 3 right   | 3             | C     |
```

Make tables by using pipes to separate columns.

Tables | Are | Cool
--- | --- | ---
1 | 2 | 3

Make your table pretty with whitespace and colons to align columns.

| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 1 left    | 1             | A     |
| col 2 center  | 2             | B     |
| col 3 right   | 3             | C     |

## Blockquotes

```
> To be or not to be,
> that is the question.
```

> To be or not to be,
> that is the question.

## Emoji

Surround emoji codes with with colons. Ignore the space after the leading colon and before the trailing one.

```
: smile :
```

:smile: :+1: :bomb:

## Math

```
Inline LaTeX $(x_1+5)$.
```

Inline LaTeX $(x_1+5)$.

```
Block LaTeX.

$[\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}\tag{1}]$
```

Block LaTeX.

$[\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}\tag{1}]$

```
Inline ASCIIMath ${x_1+5}$.
```

Inline ASCIIMath ${x_1+5}$.

```
Block ASCIIMath.

${x = (-b +- sqrt(b^2-4ac))/(2a)}$
```

Block ASCIIMath.

${x = (-b +- sqrt(b^2-4ac))/(2a)}$
