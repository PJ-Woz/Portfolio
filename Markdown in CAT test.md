How Markdown is Processed by Wordfast Pro 7 and Trados Studio 2022<!-- Omit in toc -->
===

<!-- This here is a comment. And I'd like to create a TOC below -->
<!-- Use this: https://www.markdownguide.org/cheat-sheet/ -->
<!-- Things I need to insert:
- HTML tags, like <code></code>
- (funny thing that markdown kinda works here)
-  -->

# Introduction

<p>This file is created to test how two Computer-Aided Translation programs – Wordfast Pro 7 and Trados 2022 – read markdown files.</p>

## What is a CAT?
[Computer-Aided Translation](https://en.wikipedia.org/wiki/Computer-assisted_translation) software (usually known as CAT) is a program that helps translators translate various files, including Markdown *.md files.

There are **many** diferent CATs. Two of them are *Wordfast Pro* and *Trados Studio 2022*.
## Why is This Important?
Markdown files have unusual formatting. The syntax for __bold__ can be for example: `__bold__`.  
The question arises: Will a CAT know which symbol is part of Markdown syntax and which is used as part of the text?

And to make it even spicier, I'll also include a few HTML tags to see how they are read in combination with Markdown syntax.

We'll learn soon enough.

# Markdown Syntax

## General Information

I'll group Markdown syntax into:
1. basic syntax:
   1. bold
   2. italic
   3. strikethrough
   4. ordered list
   5. unordered list
2. links:
   1. links to sections with headers
   2. links to files
   3. links to images
   4. links to websites
   5. links to YouTube
3. quotations:
   1. standard quotation
   2. inline code
   3. block code
4. extended syntax:
   1. tables
   2. definition
   3. task list
   4. emoji
   5. highlight
   6. subscript
   7. superscript
   8. hiding content with comments
   9. ignoring Markdown formatting

---

This will allow us to see which elements of Markdown syntax are – or are not – read by two CATs:
- _Wordfast Pro_
- _Trados Studio 2022_

## Basic Text Formatting

### Bold

**This text is in bold.**
__Thix text is in bold.__

### Italic

*This text is in italic.*
_This text is in italic._

### Strikethrough
~~This text is in strikethrough.~~

### Ordered List
This is a sample ordered list:
1. Item 1
2. Item 2
3. Item 3
   1. Subitem 3.1
   2. Subitem 3.2

### Unordered List
This is a sample unordered list:
- Item 1
- Item 2
- Item 3
  - Subitem 3
  - Subitem 3
  
## Links
Here we'll see how different types of links are interpreted by *Wordfast Pro* and *Trados Studio 2022*.

### Links to Sections with Headers
The link to section on [**Bold** is here](#bold).

### Links to Files
The link to [a Markdown file in the repository is here](Project-Woźnikowski-2022-11-27.md).

### Links to Images
1. The link to [an image in the repository is here](Images/IMG_20200401_210429.jpg).
2. The link to a displayed image in the repository is here:
   
   ![Shark](Images/IMG_20200401_210429.jpg)
3. The link to a displayed image in the repository with a hover text is here:
   
   ![Shark](Images/IMG_20200401_210429.jpg "A Technical Writer Shark")
4. The link to a displayed image from the internet:
   
   ![Cieszyn](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/2012_Powiat_cieszy%C5%84ski%2C_Cieszyn%2C_Rynek%2C_Fontanna_%C5%9Bw._Floriana_02.jpg/310px-2012_Powiat_cieszy%C5%84ski%2C_Cieszyn%2C_Rynek%2C_Fontanna_%C5%9Bw._Floriana_02.jpg)

### Links to Websites
The link to [my website Translatorion.com is here](https://translatorion.com/).

### Links to YouTube
The link to an embedded David Bowie video on YouTube is here:
[![I am a DJ](http://img.youtube.com/vi/MRRmU_pOXnk/0.jpg)](http://www.youtube.com/watch?v=MRRmU_pOXnk "I am what I play").

## Quotations



### Blockquote
> This is a quote

# HTML and Other Tags

1. Paragraph
2. Code
3. Collapsed Section
4. 