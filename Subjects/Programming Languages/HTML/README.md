# HTML
---
## Overview

The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. 
It can be assisted by technologies such as Cascading Style Sheets and scripting languages such as JavaScript.

+ HTML stands for Hyper Text Markup Language
+ HTML is the standard markup language for creating Web pages
+ HTML describes the structure of a Web page
+ HTML consists of a series of elements
+ HTML elements tell the browser how to display the content
+ HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

## Table of Contents

- [HTML](#html)
  * [Overview](#overview)
  * [Table of Contents](#table-of-contents)
  * [Sources](#sources)
  * [What is an HTML Element](#what-is-an-html-element)
  * [HTML Page structure](#html-page-structure)
  * [How to view source code on browser](#how-to-view-source-code-on-browser)
  * [HTML Element Anatomy](#html-element-anatomy)
  * [HTML Attributes](#html-attributes)
    + [href](#href)
    + [src](#src)
      - [Ways to specify URL in src](#ways-to-specify-url-in-src)
    + [width and height](#width-and-height)
    + [Alt Attributes](#alt-attributes)
  * [HTML Headings](#html-headings)
    + [Headings Are Important](#headings-are-important)
  * [HTML Paragraphs](#html-paragraphs)
  * [HTML Display](#html-display)
  * [Line breaks](#line-breaks)
  * [pre element](#pre-element)

## Sources

1. Wikipedia - https://en.wikipedia.org/wiki/HTML
2. W3 Schools - https://www.w3schools.com/html/default.asp

---
## What is an HTML Element

An HTML element is defined by a start tag, some content, and an end tag:

```HTML
<tagname> Content </tagname>
```

## HTML Page structure

An HTML page follows a Nested Tree Structure.

```HTML
<topElement>
	<nestedElementName>
		<moreNested>
		</moreNested>
	</nestedElementName>
	<nestedElementName>
		<moreNested>
		</moreNested>
	</nestedElementName>
	<nestedElementName>
		<moreNested>
		</moreNested>
		<nestedElementName>
			<moreNested>
			</moreNested>
		</nestedElementName>
	</nestedElementName>
</topElement>
```

## How to view source code on browser

To view source code on browser, go to the developer tools menu by pressing f12. 

## HTML Element Anatomy

An HTML element is defined by a start tag, some content, and an end tag.
HTML elements may be nested. 

## HTML Attributes

HTML attributes provide additional information about HTML elements.

### href
The href attribute specifies the URL of the page the link goes to.
```HTML
<a href="https://www.google.com">Visit google</a>
```

### src
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed.
```HTML
<img src="img.jpg">
```

#### Ways to specify URL in src

1. Absolute URL - https://www.example.com/images/img
2. Relative URL - /images/img

### width and height
The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels).
```HTML
<img src="img.jpg" width="500" height="600">
```

### Alt Attributes
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. 
This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader.
```HTML
<img src="img.jpg" alt="Man on a roof">
```


## HTML Headings 

HTML headings are defined with the <h1> to <h6> tags.

<h1> defines the most important heading. <h6> defines the least important heading.

### Headings Are Important
Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

<h1> headings should be used for main headings, followed by <h2> headings, then the less important <h3>, and so on

## HTML Paragraphs
The HTML <p> element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

## HTML Display
You cannot be sure how HTML will be displayed.

Large or small screens, and resized windows will create different results.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.

## Line breaks
The HTML <br> element defines a line break.

Use <br> if you want a line break (a new line) without starting a new paragraph.

```HTML
<p>This is<br>a paragraph<br>with line breaks.</p>
```

## pre element
The HTML <pre> element defines preformatted text.

The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

```HTML
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```