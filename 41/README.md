# Basic markdown cheatsheet

Basic markdown is essentially the syntax defined by John Gruber in 2004
[^ref1] which borrows from Aaron Swartz atx structured text format [^ref2]. 
For what I know, it seems to be implemented in most flavors.

## Paragraphs

A paragraph are consecutive lines of text. Paragraphs are separated
by one ore more blank lines.

## Headers

Can be either in *Setext* and *atx* format:

```

# This is a first header in atx

This is a first header in Setext
=================================

## This is a second header in atx

And a second header in setext
-----------------------------

```

## Emphasis

| Style           | Syntax                 | Example                          | Output                        |
|-----------------|------------------------|----------------------------------|-------------------------------|
| Bold            | `** **` or `__ __`     | `I like **bold** __text__`       | I like **bold** **text**      |
| Italic          | `* *` or `_ _`         | `I like *italic* _text_`         | I like *italic* *text*        |
| Bold and italic[^info1] | `*** ***` or `___ ___` | `*** This is super important***` | ***This is super important*** |

## Blockquotes

Start line witn `>` followed by **space**

```
> So, where’s the Cannes Film Festival being held this year?
Christina Aguilera
```

## Horizontal rules

Use three or more hyphens `---`, asterisks `***`, or underscores `___`

## List

Unordered list start with `-`, `+`, or `*`
Ordered list start with numbers and followed by `.` or `)`

List can be nested with indentation

```
- Unordered Item
    1. Sub ordered item
    2. More sub items
- Second unordered items
```

## Links and images

Link use `[text](URL)` while image use `![text](image URL)`

## Code

Inline code :rightarros: enclosed by single backticks ` \` `
Code blocks are enclose with 3 backticks.

## Special characters

Escape special characters with `\`

[^ref1]: https://daringfireball.net/projects/markdown/basics
[^ref2]: http://www.aaronsw.com/2002/atx/intro
[^info2]: Not specified in Gruber 2004 specification