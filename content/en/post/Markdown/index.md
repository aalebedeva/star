---
title: Markdown
subtitle: article about Markdown

# Summary for listings and search engines
summary: article about Markdown

# Link this post with a project
projects: 

# Date published
date: '2022-05-14T00:00:00Z'

# Date updated
lastmod: '2022-05-14T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic

categories:
  - Demo
---

## article
This document is intended to introduce the user to the functionality of the Markdown markup language. Markdown is a lightweight markup language that is a tool for converting code into HTML. The main feature of this language is the most simple syntax, which serves to simplify writing and reading the markup code, which, in turn, makes it easy to correct it. Now let's take a closer look at the features of the Markdown markup language.

Markdown is not a replacement for HTML. The syntax of Markdown is quite limited, and matches only a small subset of HTML elements. Paragraphs and line breaks

In order to create a paragraph using the syntax of the Markdown language, it is enough to separate lines of text with one (or more) empty lines (an empty line is any line that contains nothing but spaces and tabs). In order to insert a visible line break (the <br/> element), you must end the line with two spaces and press the Enter key. Many Markdown syntax elements look and work much better when formatted with "hard translation lines" (string separation carried out by the user himself, and not automatically by the program). These elements include quotes, lists, etc.

Titles

The Markdown markup language supports 2 heading styles: underlining and highlighting with the symbol ("#"). Highlighting headings using underlining is done with equal signs ("=") if the heading is the first level, and hyphens ("-") if the heading is the second level. The number of underscores is not limited. When highlighting headings using the symbol ("#"), one to six of these characters are used, which are set at the beginning of the line (before the heading). In this case, the number of characters corresponds to the heading level. In addition, it is possible to provide closing characters ("#") in the title, although this is not required. The number of closing characters does not have to match the number of beginning characters. The title level is determined by the number of initial characters.

Quotes

Markdown uses the greater-than sign (>) to indicate quotes. It can be inserted both before each line of a quotation, and only before the first line of a paragraph. Markdown syntax also allows you to create nested quotes (quotes within quotes). Additional levels of quotation marks (">") are used to mark them up. Quotes in Markdown can contain all sorts of markup elements.

Lists

Markdown supports ordered (numbered) and unordered (unordered) lists. To form unordered lists, markers such as asterisks, pluses, and hyphens are used. All listed markers can be used interchangeably. Dotted numbers are used as markers to form ordered lists. An important feature in this case is that the numbers themselves, with which the list is formed, are not important, since they do not affect the output HTML code. No matter how the user numbers the list, in the output he will in any case have an ordered list starting from one (1, 2, 3 ...). This feature should be taken into account when it is necessary to use the serial numbers of elements in the list so that they correspond to the numbers obtained in HTML. Ordered lists should always start with one. List markers usually start at the beginning of the line, but they can be shifted up to a maximum of 3 spaces. The marker must be followed by a space or a tab character. You can insert a citation into the list if necessary. In this case, quoting marks ( ">" ) must be indented. It can be used in Markdown before special characters so that they are perceived in their literal (and not official) meaning. The full list of these symbols is given below:

"\" - slash;

"`" - backtick;

"*" - asterisk;

"_" - underscore character;

"{}" - curly braces;

"[]" - square brackets;

"()" - round brackets;

"#" - hash symbol;

"+" - plus;

"-" - minus (hyphen);

"." - dot;

"!" - Exclamation point.
