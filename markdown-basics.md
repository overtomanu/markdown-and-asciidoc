# Markdown basics

- [Markdown basics](#markdown-basics)
- [Headings / titles](#headings--titles)
- [Header one](#header-one)
  - [Header two](#header-two)
    - [Header three](#header-three)
      - [Header four](#header-four)
        - [Header five](#header-five)
          - [Header six](#header-six)
- [Alternate syntax](#alternate-syntax)
- [Heading level 1](#heading-level-1)
  - [Heading level 2](#heading-level-2)
- [Lists](#lists)
  - [ordered / numbered list](#ordered--numbered-list)
  - [unordered lists](#unordered-lists)
- [bolded and other formatted texts](#bolded-and-other-formatted-texts)
  - [line break](#line-break)
  - [horizontal rule](#horizontal-rule)
  - [URLs and Email Addresses](#urls-and-email-addresses)
  - [strikethrough](#strikethrough)
  - [highlight](#highlight)
  - [text with color](#text-with-color)
  - [subscript](#subscript)
  - [superscript](#superscript)
  - [task list](#task-list)
  - [multiline block quote](#multiline-block-quote)
  - [Escaping text](#escaping-text)
  - [code block](#code-block)
  - [syntax highlighted code block](#syntax-highlighted-code-block)
  - [Showing table in markdown](#showing-table-in-markdown)
- [Paragraphs](#paragraphs)
- [Links](#links)
  - [image display from link](#image-display-from-link)
  - [referenced links](#referenced-links)
- [expand / details collapse](#expand--details-collapse)
- [Footnotes](#footnotes)


# Headings / titles

# Header one

## Header two

### Header three

#### Header four

##### Header five

###### Header six

# Alternate syntax

Heading level 1
===============

Heading level 2
---------------

# Lists

## ordered / numbered list

1. numbered list
   1. nested
      - bulleted
3. actual numbers can be anything
2. and can be out of order

## unordered lists

- this
- is
- unordered
  - nested
- list

* use star or underscore to create unordered list

# bolded and other formatted texts

_this is italicised text_

*this is emphasized text*
  
>this is block quote text.
>lines are combined

## line break

You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application.
This will not be rendered in new line  
whereas this line will be in new line

## horizontal rule

use three hyphes or three stars to create horizontal rule

---
or
***

## URLs and Email Addresses

<https://www.markdownguide.org>

<fake@example.com>

## strikethrough

~~The world is flat.~~ We now know that the world is round.

## highlight

I need to highlight these ==very important words==.
Or use HTML tag <mark>very important words</mark>

## text with color

This is text with color (using inline code block) `very important words`

## subscript

H<sub>2</sub>O

## superscript

X<sup>2</sup>

## task list

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## multiline block quote

> this is 
>multiline block quote
>test line 3
>
>line after blank line

## Escaping text

this is a escaped `<html></html>` tag

## code block
```
This is fenced code segment using three backticks
can be multiline
```

    or indent four space to create code block
    or a tab

## syntax highlighted code block

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Showing table in markdown

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| left aligned as colon is on left      | Title       | Here's this   |
| Paragraph   | Middle aligned as there is colon on both sides        | Right aligned as colon is only present on right      |

# Paragraphs

This is a multiline paragraph  
Insert two spaces at the end of previous line to have soft line break (force new line) after a sentence

Insert a blank line to create new paragraph

# Links

This is a github link [Visit GitHub!](www.github.com)

## image display from link
![pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

## referenced links

Here's [a link to something else][another place].
Here's [yet another link][another-link].
And now back to [the first link][another place].

[another place]: www.github.com
[another-link]: www.google.com

# expand / details collapse

<details>
  <summary>Click me</summary>
  
  1. Foo
  2. Bar
     * Baz
     * Qux

</details>
<br></br>

# Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.
