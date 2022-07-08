# HTML Concepts, Intuition, Applications, and Examples

## Table of Contents  

- [HTML Concepts, Intuition, Applications, and Examples](#html-concepts--intuition--applications--and-examples)
  * [Table of Contents](#table-of-contents)
  * [Sources used](#sources-used)
- [Section 1, HTML Basics](#section-1--html-basics)
  * [Concept 1, What is HTML?](#concept-1--what-is-html-)
      - [Some Terminology](#some-terminology)
    + [HTML compared to Other Web Languages](#html-compared-to-other-web-languages)
    + [Example: HTML Tags and Nested Tags](#example--html-tags-and-nested-tags)
    + [Applications of HTML](#applications-of-html)
      - [Web Page Serving Methods](#web-page-serving-methods)
      - [Embedding Media into websites](#embedding-media-into-websites)
  * [Concept 2, How to Play with HTML](#concept-2--how-to-play-with-html)
    + [Why you should play with HTML](#why-you-should-play-with-html)
    + [Using Developer Tools to Edit HTML](#using-developer-tools-to-edit-html)
      - [Why you should use Dev TOols](#why-you-should-use-dev-tools)
      - [When you shouldn't use Dev Tools](#when-you-shouldn-t-use-dev-tools)
      - [How to Edit HTML With Dev Tools](#how-to-edit-html-with-dev-tools)
    + [Using CodePen to Edit HTML](#using-codepen-to-edit-html)
      - [Why you should use Code Pen](#why-you-should-use-code-pen)
      - [When you shouldn't use Code Pen](#when-you-shouldn-t-use-code-pen)
      - [How to Edit HTML With Code Pen](#how-to-edit-html-with-code-pen)
    + [Using VSCode to edit Code](#using-vscode-to-edit-code)
      - [Why you should use an IDE like VSCode](#why-you-should-use-an-ide-like-vscode)
      - [When you shouldn't use an IDE like VSCode](#when-you-shouldn-t-use-an-ide-like-vscode)
      - [How to Edit HTML With an IDE like VSCode](#how-to-edit-html-with-an-ide-like-vscode)
  * [Concept 3, Stucture and Anatomy of HTML](#concept-3--stucture-and-anatomy-of-html)
    + [Introduction to the DOM](#introduction-to-the-dom)
    + [Anatomy of an HTML Element](#anatomy-of-an-html-element)
    + [Attributes of an HTML Element](#attributes-of-an-html-element)
    + [Attributes of an HTML Page](#attributes-of-an-html-page)
    + [HTML Entities, how to escape special characters in HTML](#html-entities--how-to-escape-special-characters-in-html)
    + [Section Summary (All Cheat Sheet Items)](#section-summary--all-cheat-sheet-items-)
  * [Concept 4, HTML Head](#concept-4--html-head)
    + [What is the Head?](#what-is-the-head-)
    + [Example: Adding a Title](#example--adding-a-title)
    + [Example: Open Graph Data and Twitter Cards](#example--open-graph-data-and-twitter-cards)
    + [Example: Adding Custom Icons](#example--adding-custom-icons)
    + [Example: Script Tags and CSS](#example--script-tags-and-css)
  * [Concept 5, HTML Text](#concept-5--html-text)
    + [Structural Hierarchy](#structural-hierarchy)
    + [Why We need structure](#why-we-need-structure)
    + [Lists](#lists)
      - [Unordered](#unordered)
      - [Ordered](#ordered)
  * [Concept 6, HTML Links](#concept-6--html-links)
  * [Concept 7, HTML Website Structure](#concept-7--html-website-structure)
- [Section 2, Media , Embedding, and Graphics](#section-2--media---embedding--and-graphics)
  * [Concept 8, Images](#concept-8--images)
  * [Concept 9, Video and Audio](#concept-9--video-and-audio)
  * [Concept 10, iframes](#concept-10--iframes)
  * [Concept 11, Vector Graphics and Canvas](#concept-11--vector-graphics-and-canvas)
- [Section 3, HTML Tables](#section-3--html-tables)
  * [Concept 12, Table Basics](#concept-12--table-basics)
  * [Concept 13, Advanced Tables](#concept-13--advanced-tables)
  * [Concept 14, Table Accessibility](#concept-14--table-accessibility)
- [Section 4, HTML Forms](#section-4--html-forms)
  * [Concept 15, Form Introduction](#concept-15--form-introduction)
  * [Concept 16, Form Attributes](#concept-16--form-attributes)
  * [Concept 17, Form Elements](#concept-17--form-elements)
  * [Concept 18, Input Types](#concept-18--input-types)
  * [Concept 19, Input Attributes](#concept-19--input-attributes)
  * [Concept 20, Input Form Attributes](#concept-20--input-form-attributes)
- [Section 5, HTML APIs](#section-5--html-apis)
  * [Concept 21, HTML Geolocation](#concept-21--html-geolocation)
  * [Concept 22, HTML Drag/Drop](#concept-22--html-drag-drop)
  * [Concept 23, Web Storage](#concept-23--web-storage)
  * [Concept 24, Web Workers](#concept-24--web-workers)
  * [Concept 25, SSE](#concept-25--sse)

## Sources used

1. [CSR vs SSR vs SSG](https://www.section.io/engineering-education/client-side-rendering-vs-server-side-rendering-vs-static-site-generation/)
2. [Code Pen](https://codepen.io/)
3. [VSCode](https://code.visualstudio.com/Download)
4. [HTML VSCode Tutorial ](https://www.youtube.com/watch?v=ndEFbDOsM6c)

---

# Section 1, HTML Basics

## Concept 1, What is HTML?

HTML is the Markup Language used on Websites to define the __Content__ of the page. 
HTML Stands for __Hyper Text Markup Language__.
HTML is a series of _Tags with Attributes_, with _Nested Content inside it_. 
HTML is responsible for __What__ is displayed, not  for __How__ it is displayed. 

#### Some Terminology

+ __Tags__ - The HTML Element that defines the semantic meaning of some website content. 
	+ &ltp&gt p tag semantically means paragraphs of text &lt/p&gt
+ __Tag Attributes__ - This adds meaning to the Tag so that HTML knows how to Display the Element Properly.

### HTML compared to Other Web Languages

Below is a table comparing what HTML is responsible for when compared to other web languages.

Language | Responsibility | Example Code Snippet |
-----------| ----------------| --------------------------|
HTML       |  __Display__ Web Content |  &ltp&gt Hello HTML &lt/p&gt|
CSS          |  __Style__ Web Content     | div { color: red; background: green;} |
Javascript |  __Logic__ of Web Content | let f = () => { console.log("hello world"); }|

### Example: HTML Tags and Nested Tags

```HTML
<!-- Comments in HTML -->

<body>
	<p> I am content inside of a tag </p>
	<div> 
		<p> I am a nested tag inside of div </p> 
	</div>
	<a href="https://www.google.com">I am a link. My href is an attribute!</a>
</body>
```

### Applications of HTML

Since HTML is the back bone of the web, there are many applications of it. This section will name just a few to show you _why you are learning HTML_ as a developer.

#### Web Page Serving Methods
Since HTML is responsible for displaying the web content, it serves as the backbone for all websites. Even for websites that are using frameworks like __React__ or __Angular__, they somehow serve the Client's browser HTML. The only difference is in the Methods in which the HTML is generated.

Below are some of the common methods of serving HTML to client browsers:

HTML Serving Method | Brief Description | Examples of Usage | Pros/Cons |
-----------| ----------------| --------------------------| -----------------------|
Client Side Rendering | A Server sends _Javascript_ to Browser so that HTML is generated dynamically |  React JS Library | Can Be Slow to Render _at first_ and bad for __SEO__ , but dynamic reloads maximize performance after initial render |
 Server Side Rendering | A Server makes an HTML page and sends that to the Browser|  Next JS | Faster Render and better for __SEO__, but slower page transitions and complex caching |
Static Site Generation |  A __CDN__ or Server sends a pre-built HTML page. SSG generators __automate HTML creation__ | Next JS, Gatsby | Very Fast, but only good for mostly static sites like Doc pages |

see also: [CSR vs SSR vs SSG](https://www.section.io/engineering-education/client-side-rendering-vs-server-side-rendering-vs-static-site-generation/)


#### Embedding Media into websites
HTML can allow you to embed Media into websites, such as __Video__ or __Audio__. 

Below is example code for how to embed video.

```HTML
<video width="640" height="480" controls> 
	<source src="" type="video/mp4"> 
</video>
```

![Embedded Video](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content/simple-video.png)
_Embedded Video Example_

Below is example code for how to embed audio.

```HTML
<audio controls>
	<source src="name.mp3" type="audio/mp3" />
</audio>
```

![Embedded Audio](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190717125925/Screenshot-from-2019-07-17-12-58-11.png)
_Embedded Audio Example_

You may also embed __Other Websites__ in your HTML page using _iframe_ elements. 
This is common when you want to embed your _Youtube Video_ or your _SoundCloud_ into your website you are making. To do this, you usually will need to go to the host website and use their embed feature. 

Below is an Example of a Youtube Embed iframe from a music video I enjoy.
```HTML
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgauD-Dzhbc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```


## Concept 2, How to Play with HTML

There are multiple methods of playing with HTML interactively. Some include:

1. Doing it directly from your browser by using Developer tools
2. Going to Code Pen and using their playground
3. Dowloading VSCode and Editing using the IDE

### Why you should play with HTML

You will only learn HTML if you mess with it and experiment with it yourself. Therefore, __the best way to learn is by doing__.

### Using Developer Tools to Edit HTML

Knowing your way around the __Developer Tools__ is an essential skill for any web developer. For now you may just focus on using Dev tools to Edit HTML for Websites. The downside of doing it this way is that it is _hard to make your own HTML content_ directly from dev tools.
Dev tools is mainly used for _Debugging your applications_ you make with an _IDE like VSCode_.

#### Why you should use Dev TOols

You should use dev tools when you need to:

1. Quickly Prototype code or see how a change will affect your site. 
2. When you need to Debug Code
3. When you want to learn how Websites work for yourself

#### When you shouldn't use Dev Tools

You should __not__ use dev tools when you need to:

1. Develop a Non-Trivial Application
2. Write Lots of Logic

#### How to Edit HTML With Dev Tools

To edit HTML using Developer tools:

1. Navigate to your favorite webpage
2. Press f12 or access developer tools
3. Click on the HTML of the web page, and right click
4. From here you may:
	1. Add Attributes
	2. Edit Attributes
	3. Edit as HTML
	4. Duplicate
	5. Delete
	6. ....

![Developer Tools Example](https://raw.githubusercontent.com/Nellak2017/Developer-Curriculum/main/Subjects/Programming%20Languages/HTML/assets/Developer%20Tools%20Example.PNG)
_Developer Tools Example_


### Using CodePen to Edit HTML

CodePen is another method of Editing HTML. It is highly _effective for learning_ how to make websites yourself and _rapid prototyping_ without the heaviness of IDEs.

#### Why you should use Code Pen

You should use Code Pen when you need to:

1. Quickly Prototype code or try a new idea. 
2. When you want to learn how HTML works
3. When you want to see what others have made on CodePen

#### When you shouldn't use Code Pen

You should __not__ use dev tools when you need to:

1. Develop a production ready app
2. Make a huge application

#### How to Edit HTML With Code Pen

Simply go to [Code Pen](https://codepen.io/) , sign up for free and start editing!

![Code Pen Example](https://raw.githubusercontent.com/Nellak2017/Developer-Curriculum/main/Subjects/Programming%20Languages/HTML/assets/Code%20Pen%20Example.PNG)

The advantage of using Code Pen is that you can easily see how the Code works and it will allow you to fix mistakes rapidly. 

For example, I put in an mistake with the HTML Comments:

```HTML
<-- Not an HTML Comment -->
```

Then I was able to see in Code Pen the mistake and was able to adjust accordingly:

```HTML
<!-- This is a comment in HTML --> 
```

### Using VSCode to edit Code

VSCode is another method of Editing HTML. It is highly _effective for building Real Projects_ and getting Job Ready.

#### Why you should use an IDE like VSCode

You should use VSCode when you need to:

1. Make a real project
2. Have Quality Of Life Developer Extensions to make Editing Code easier
3. Contribute to Github Seamlessly

#### When you shouldn't use an IDE like VSCode

You should __not__ use dev tools when you need to:

1. Prototype
2. Run Code Snippets

#### How to Edit HTML With an IDE like VSCode

Simply go to [VSCode](https://code.visualstudio.com/Download) , download it for your OS and follow the youtube tutorial [here](https://www.youtube.com/watch?v=ndEFbDOsM6c).

![VSCode Example](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Frynne.es%2FMPDA-PythonProgramming-2020%2Fassets%2Fimg%2Fvscode-initial-screen.png&f=1&nofb=1)

The advantage of using VSCode is that you can easily make production ready projects and get Job Ready faster. 

## Concept 3, Stucture and Anatomy of HTML

Resources: [Mozilla Web Docs, Getting Started With HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

### Introduction to the DOM
So previously you got a rough overview of what HTML is, here I will go into further detail.
Essentially, Every HTML Page is a series of Elements nested inside each other in a _Tree Structure_ called the __DOM__. The __DOM__ is the _Document Object Model_, it is a tree representation of all the Nodes in a Page. 

### Anatomy of an HTML Element

![HTML Element Anatomy](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

The anatomy is:

+ Opening Tag - Name of the element, wrapped in the opening and closing brackets.
+ Content - Content of the Element.
+ Closing Tag - Same as Opening, but with an extra / to denote it's ending. 

### Attributes of an HTML Element

![Attributes of an HTML Element](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-attribute-small.png)

HTML Attributes have extra information for the Element, that won't display. 

An attribute should have:

-   A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
-   The attribute name, followed by an equal sign.
-   An attribute value, wrapped with opening and closing quote marks.

### Attributes of an HTML Page

Individual HTML elements aren't very useful on their own. Next, let's examine how individual elements combine to form an entire HTML page:

```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

Here we have:

1.  `<!DOCTYPE html>`: The doctype. When HTML was young (1991-1992), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML. Doctypes used to look something like this:
    
    ```HTML
    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
    ```
    
    More recently, the doctype is a historical artifact that needs to be included for everything else to work right. `<!DOCTYPE html>` is the shortest string of characters that counts as a valid doctype. That is all you need to know!
2.  `<html></html>`: The [`<html>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html) element. This element wraps all the content on the page. It is sometimes known as the root element.
3.  `<head></head>`: The [`<head>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) element. This element acts as a container for everything you want to include on the HTML page, **that isn't the content** the page will show to viewers. This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. You will learn more about this in the next article of the series.
4.  `<meta charset="utf-8">`: The [`<meta>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta) element. This element represents metadata that cannot be represented by other HTML meta-related elements, like [`<base>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base), [`<link>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link), [`<script>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script), [`<style>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/style) or [`<title>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title). The [`charset`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attr-charset) attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain. There is no reason not to set this, and it can help avoid some problems later.
5.  `<title></title>`: The [`<title>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title) element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.
6.  `<body></body>`: The [`<body>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body) element. This contains _all_ the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.

### HTML Entities, how to escape special characters in HTML

In HTML, the characters `<`, `>`,`"`,`'` and `&` are special characters. They are parts of the HTML syntax itself. So how do you include one of these special characters in your text? For example, if you want to use an ampersand or less-than sign, and not have it interpreted as code.

You do this with character references. These are special codes that represent characters, to be used in these exact circumstances. Each character reference starts with an ampersand (&), and ends with a semicolon (;).

Literal character | Character reference equivalent |
------------- | ------------- |
< | `&lt;` |
> | `&gt;` |
" | `&quot;` |
' | `&apos;` |
& |  `&amp;` |

The character reference equivalent could be easily remembered because the text it uses can be seen as less than for '&lt;' , quotation for ' &quot; ' and similarly for others. To find more about entity reference, see [List of XML and HTML character entity references](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references)


### Section Summary (All Cheat Sheet Items)

## Concept 4, HTML Head
The HTML __head__ is not displayed in the web page, but it offers important metadata for search engines, information for changing certain website information like your `<title>`, and links to fonts and  _CSS_ and other _Scripts_.

### What is the Head?
```HTML
<head>
 <meta charset="utf-8">
 <title>Website name</title>
</head>
```

The HTML head is the contents of the [`<head>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) element. Unlike the contents of the [`<body>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body) element (which are displayed on the page when loaded in a browser), the head's content is not displayed on the page. Instead, the head's job is to contain [metadata](https://developer.mozilla.org/en-US/docs/Glossary/Metadata) about the document.

In larger pages however, the head can get quite large. Try going to some of your favorite websites and use the [developer tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools) to check out their head contents. Our aim here is not to show you how to use everything that can possibly be put in the head, but rather to teach you how to use the major elements that you'll want to include in the head, and give you some familiarity. Let's get started.

### Example: Adding a Title

As you travel around the web, you'll find other types of metadata, too. A lot of the features you'll see on websites are proprietary creations, designed to provide certain sites (such as social networking sites) with specific pieces of information they can use.

For example, [Open Graph Data](https://ogp.me/) is a metadata protocol that Facebook invented to provide richer metadata for websites. In the MDN Web Docs sourcecode, you'll find this:

```HTML
<head>
  <meta charset="utf-8">
  <title>My test page</title>
</head>
```

### Example: Open Graph Data and Twitter Cards

```HTML
<head>
	<meta property="og:image" content="https://developer.mozilla.org/static/img/opengraph-logo.png">

	<meta property="og:description" content="The Mozilla Developer Network (MDN) provides
information about Open Web technologies including HTML, CSS, and APIs for both Web sites
and HTML5 Apps. It also documents Mozilla products, like Firefox OS.">

	<meta property="og:title" content="Mozilla Developer Network">
</head>
```

![Facebook Open Graph](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML/facebook-output.png)
_Facebook Open Graph Meta-data_

Twitter also has its own similar proprietary metadata called [Twitter Cards](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards), which has a similar effect when the site's URL is displayed on twitter.com. For example:

```HTML
<meta name="twitter:title" content="Mozilla Developer Network">
```

### Example: Adding Custom Icons
To further enrich your site design, you can add references to custom icons in your metadata, and these will be displayed in certain contexts. The most commonly used of these is the **favicon** (short for "favorites icon", referring to its use in the "favorites" or "bookmarks" lists in browsers).

The humble favicon has been around for many years. It is the first icon of this type: a 16-pixel square icon used in multiple places. You may see (depending on the browser) favicons displayed in the browser tab containing each open page, and next to bookmarked pages in the bookmarks panel.

A favicon can be added to your page by:

1.  Saving it in the same directory as the site's index page, saved in `.ico` format (most browsers will support favicons in more common formats like `.gif` or `.png`, but using the ICO format will ensure it works as far back as Internet Explorer 6.)
2.  Adding the following line into your HTML's [`<head>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) block to reference it:
    
```HTML
    <link rel="icon" href="favicon.ico" type="image/x-icon">
```

Here is an example of a favicon in a bookmarks panel:

![Favicon Example](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML/bookmark-favicon.png)
_Favicon Example_

### Example: Script Tags and CSS
Just about all websites you'll use in the modern day will employ [CSS](https://developer.mozilla.org/en-US/docs/Glossary/CSS) to make them look cool, and [JavaScript](https://developer.mozilla.org/en-US/docs/Glossary/JavaScript) to power interactive functionality, such as video players, maps, games, and more. These are most commonly applied to a web page using the [`<link>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) element and the [`<script>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) element, respectively.

-   The [`<link>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) element should always go inside the head of your document. This takes two attributes, `rel="stylesheet"`, which indicates that it is the document's stylesheet, and `href`, which contains the path to the stylesheet file:
    
	```HTML
    <link rel="stylesheet" href="my-css-file.css">
	```

    
-   The [`<script>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) element should also go into the head, and should include a `src` attribute containing the path to the JavaScript you want to load, and `defer`, which basically instructs the browser to load the JavaScript after the page has finished parsing the HTML. This is useful as it makes sure that the HTML is all loaded before the JavaScript runs, so that you don't get errors resulting from JavaScript trying to access an HTML element that doesn't exist on the page yet. There are actually a number of ways to handle loading JavaScript on your page, but this is the most reliable one to use for modern browsers (for others, read [Script loading strategies](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#script_loading_strategies)).
    
	```HTML
    <script src="my-js-file.js" defer></script>
	```

## Concept 5, HTML Text

Resources: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

Structured content makes the reading experience easier and more enjoyable. That is why learning how to Format Text in HTML is important. You need to Format your HTML to be _Semantic_ and _Organized_.

### Structural Hierarchy

For example, in this story, the `<h1>` element represents the title of the story, the `<h2>` elements represent the title of each chapter, and the `<h3>` elements represent sub-sections of each chapter:

```HTML
<h1>The Crushing Bore</h1>

<p>By Chris Mills</p>

<h2>Chapter 1: The dark night</h2>

<p>It was a dark night. Somewhere, an owl hooted. The rain lashed down on the ...</p>

<h2>Chapter 2: The eternal silence</h2>

<p>Our protagonist could not so much as a whisper out of the shadowy figure ...</p>

<h3>The specter speaks</h3>

<p>Several more hours had passed, when all of a sudden the specter sat bolt upright and exclaimed, "Please have mercy on my soul!"</p>
```


It's really up to you what the elements involved represent, as long as the hierarchy makes sense. You just need to bear in mind a few best practices as you create such structures:

-   Preferably, you should use a single `<h1>` per page—this is the top level heading, and all others sit below this in the hierarchy.
-   Make sure you use the headings in the correct order in the hierarchy. Don't use `<h3>` elements to represent subheadings, followed by `<h2>` elements to represent sub-subheadings—that doesn't make sense and will lead to weird results.
-   Of the six heading levels available, you should aim to use no more than three per page, unless you feel it is necessary. Documents with many levels (for example, a deep heading hierarchy) become unwieldy and difficult to navigate. On such occasions, it is advisable to spread the content over multiple pages if possible.

### Why We need structure
Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are applied. (Do any countries use red to mean "go"? We hope not.)

In a similar vein, we need to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance. In this context, the [`<h1>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) element is also a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

### Lists

#### Unordered
To make, wrap list items in a `ul` then for each element wrap that in `li`.

```HTML
<ul>
 <li> milk </li> 
 <li> eggs </li>
 <li> bread </li>
 <li> hummus </li>
</ul>
```

It will naturally display as a list of _Bullet Points_. You may use CSS to style the bullet points away. 

#### Ordered
To make, wrap list items in a `ol` then for each element wrap that in `li`.

```HTML
<ol>
 <li> milk </li> 
 <li> eggs </li>
 <li> bread </li>
 <li> hummus </li>
</ol>
```

It will naturally display as a numbered list.

## Concept 6, HTML Links
## Concept 7, HTML Website Structure

# Section 2, Media , Embedding, and Graphics
## Concept 8, Images 
## Concept 9, Video and Audio 
## Concept 10, iframes
## Concept 11, Vector Graphics and Canvas

# Section 3, HTML Tables
## Concept 12, Table Basics
## Concept 13, Advanced Tables
## Concept 14, Table Accessibility

# Section 4, HTML Forms
## Concept 15, Form Introduction
## Concept 16, Form Attributes
## Concept 17, Form Elements
## Concept 18, Input Types
## Concept 19, Input Attributes
## Concept 20, Input Form Attributes

# Section 5, HTML APIs
## Concept 21, HTML Geolocation
## Concept 22, HTML Drag/Drop
## Concept 23, Web Storage
## Concept 24, Web Workers
## Concept 25, SSE


