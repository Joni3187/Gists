# HTML - MDN - MarkDown
Hyper Text Markup Language: Elements used to annotate content for display in a Web Browser.


## HTML Elements Reference
This page lists all the HTML elements, which are created using tags.
They are grouped by function to help you find what you have in mind easily. An alphabetical list of
all elements is provided in the sidebar on every element's page as well as this one. 
*Note: For more information about the basics of HTML elements and attributes, see the section on elements in the Introduction to HTML article.


<!-- MAIN ROOT  -->


## Main root

### HTML
```
<html> 
```
The ```<html>``` HTML element represents the root (top-level element) of an HTML document, so it is also referred to as the root element. All other elements must be descendants of this element.

  
<!-- DOCUMENT METADATA -->
  
  
## Document metadata
Metadata contains information about the page. This includes information about styles, 
scripts and data to help software (search engines, browsers, etc.) use and render the page. 
Metadata for styles and scripts may be defined in the page or link to another file that has the information.

### BASE
```
<base>
```
The ```<base>``` HTML element specifies the base URL to use for all relative URLs in a document. There can be only one ```<base>``` element in a document.

### HEAD
```
<head>
```
The ```<head>``` HTML element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.
  
### LINK
```
<link>
```
The ```<link>``` HTML element specifies relationships between the current document and an external resource. This element is most commonly used to link to CSS, but is also used to establish site icons (both "favicon" style icons and icons for the home screen and apps on mobile devices) among other things.

### META
```
<meta>
```
The ```<meta>``` HTML element represents Metadata that cannot be represented by other HTML meta-related elements, like base, link, script, style or title.

### STYLE
```
<style>
```	
The ```<style>``` HTML element contains style information for a document, or part of a document. It contains CSS, which is applied to the contents of the document containing the ```<style>``` element.

### TITLE
```
<title>
```    
The ```<title>``` HTML element defines the document's title that is shown in a Browser's title bar or a page's tab. It only contains text; tags within the element are ignored.

  
<!-- SECTIONING ROOT  -->
  
  
## Sectioning root
  
### BODY
```
<body>
```
The ```<body>``` HTML element represents the content of an HTML document. There can be only one ```<body>``` element in a document.
  
  
<!-- CONTENT SECTIONING -->
  
  
## Content sectioning
Content sectioning elements allow you to organize the document content into logical pieces. Use the sectioning elements to create a broad outline for your page content, including header and footer navigation, and heading elements to identify sections of content.

### ADDRESS
```
<address>
```
The ```<address>``` HTML element indicates that the enclosed HTML provides contact information for a person or people, or for an organization.
  
### ARTICLE
```
<article>
```
The ```<article>``` HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
  
### ASIDE
```
<aside>
```
The ```<aside>``` HTML element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.
      
### FOOTER
```
<footer>
```
The ```<footer>``` HTML element represents a footer for its nearest ancestor sectioning content or sectioning root element. A ```<footer>``` typically contains information about the author of the section, copyright data or links to related documents.
        
### HEADER
```
<header>
```
The ```<header>``` HTML element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.
          
### SECTION HEADINGS
```
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>
```
The ```<h1>``` to ```<h6>``` HTML elements represent six levels of section headings. ```<h1>``` is the highest section level and ```<h6>``` is the lowest.
            
### MAIN
```
<main>
```
The ```<main>``` HTML element represents the dominant content of the body of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.
              
### NAV
```
<nav>
```
The ```<nav>``` HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.
                
### SECTION
```
<section>
```
The ```<section>``` HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.

  
<!-- TEXT CONTENT -->
                  
                  
## Text content
Use HTML text content elements to organize blocks or sections of content placed between the opening ```<body>``` and closing ```</body>``` tags. Important for accessibility and SEO, these elements identify the purpose or structure of that content.

### BLOCKQUOTE
```
<blockquote>
```
The ```<blockquote>``` HTML element indicates that the enclosed text is an extended quotation. Usually, this is rendered visually by indentation (see Notes for how to change it). A URL for the source of the quotation may be given using the cite attribute, while a text representation of the source can be given using the cite element.
  
### DD
```
<dd>
```
The ```<dd>``` HTML element provides the description, definition, or value for the preceding term (dt) in a description list (dl).

### DIV
```
<div>
```
The ```<div>``` HTML element is the generic container for flow content. It has no effect on the content or layout until styled in some way using CSS (e.g., styling is directly applied to it, or some kind of layout model like Flexbox is applied to its parent element).

### DL
```
<dl>
```	
The ```<dl>``` HTML element represents a description list. The element encloses a list of groups of terms (specified using the dt element) and descriptions (provided by dd elements). Common uses for this element are to implement a glossary or to display metadata (a list of key-value pairs).
  
### DT
```
<dt>
```	
The ```<dt>``` HTML element specifies a term in a description or definition list, and as such must be used inside a dl element. It is usually followed by a dd element; however, multiple ```<dt>``` elements in a row indicate several terms that are all defined by the immediate next dd element.
  
### FIGCAPTION
```
<figcaption>
```	
The ```<figcaption>``` HTML element represents a caption or legend describing the rest of the contents of its parent figure element.
  
### FIGURE
```
<figure>
```	
The ```<figure>``` HTML element represents self-contained content, potentially with an optional caption, which is specified using the figcaption element. The figure, its caption, and its contents are referenced as a single unit.
  
### HR
```
<hr>
```	
The ```<hr>``` HTML element represents a thematic break between paragraph-level elements: for example, a change of scene in a story, or a shift of topic within a section.
  
### LI
```
<li>
```	
The ```<li>``` HTML element is used to represent an item in a list. It must be contained in a parent element: an ordered list (ol), an unordered list (ul), or a menu (menu). In menus and unordered lists, list items are usually displayed using bullet points. In ordered lists, they are usually displayed with an ascending counter on the left, such as a number or letter.
  
### MENU
```
<menu>
```	
The ```<menu>``` HTML element is described in the HTML specification as a semantic alternative to ul, but treated by browsers (and exposed through the accessibility tree) as no different than ul. It represents an unordered list of items (which are represented by li elements).
  
### OL
```
<ol>
```	
The ```<ol>``` HTML element represents an ordered list of items — typically rendered as a numbered list.
  
### P
```
<p>
```	
The ```<p>``` HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.
  
### PRE
```
<pre>
```	
The ```<pre>``` HTML element represents preformatted text which is to be presented exactly as written in the HTML file. The text is typically rendered using a non-proportional, or monospaced, font. Whitespace inside this element is displayed as written.

### UL
```
<ul>
```	
The ```<ul>``` HTML element represents an unordered list of items, typically rendered as a bulleted list.


<!-- INLINE TEXT SEMANTICS -->


## Inline text semantics
Use the HTML inline text semantic to define the meaning, structure, or style of a word, line, or any arbitrary piece of text.

### 
```
<a>
```	
The ```<a>``` HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

### 
```
<abbr>
```	
The ```<abbr>``` HTML element represents an abbreviation or acronym; the optional title attribute can provide an expansion or description for the abbreviation. If present, title must contain this full description and nothing else.

### 
```
<b>
```	
The ```<b>``` HTML element is used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use <b> for styling text; instead, you should use the CSS font-weight property to create boldface text, or the strong element to indicate that text is of special importance.

### 
```<bdi>```	The ```<bdi>``` HTML element tells the browser's bidirectional algorithm to treat the text it contains in isolation from its surrounding text. It's particularly useful when a website dynamically inserts some text and doesn't know the directionality of the text being inserted.

```<bdo>```	The ```<bdo>``` HTML element overrides the current directionality of text, so that the text within is rendered in a different direction.

```<br>```	The ```<br>``` HTML element produces a line break in text (carriage-return). It is useful for writing a poem or an address, where the division of lines is significant.

<cite>	The <cite> HTML element is used to describe a reference to a cited creative work, and must include the title of that work. The reference may be in an abbreviated form according to context-appropriate conventions related to citation metadata.

<code>	The <code> HTML element displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code. By default, the content text is displayed using the user agent default monospace font.

<data>	The <data> HTML element links a given piece of content with a machine-readable translation. If the content is time- or date-related, the time element must be used.

<dfn>	The <dfn> HTML element is used to indicate the term being defined within the context of a definition phrase or sentence. The p element, the dt/dd pairing, or the section element which is the nearest ancestor of the <dfn> is considered to be the definition of the term.

<em>	The <em> HTML element marks text that has stress emphasis. The <em> element can be nested, with each level of nesting indicating a greater degree of emphasis.

<i>	The <i> HTML element represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, taxonomical designations, among others. Historically, these have been presented using italicized type, which is the original source of the <i> naming of this element.

<kbd>	The <kbd> HTML element represents a span of inline text denoting textual user input from a keyboard, voice input, or any other text entry device. By convention, the user agent defaults to rendering the contents of a <kbd> element using its default monospace font, although this is not mandated by the HTML standard.

<mark>	The <mark> HTML element represents text which is marked or highlighted for reference or notation purposes, due to the marked passage's relevance or importance in the enclosing context.

<q>	The <q> HTML element indicates that the enclosed text is a short inline quotation. Most modern browsers implement this by surrounding the text in quotation marks. This element is intended for short quotations that don't require paragraph breaks; for long quotations use the blockquote element.

<rp>	The <rp> HTML element is used to provide fall-back parentheses for browsers that do not support display of ruby annotations using the ruby element. One <rp> element should enclose each of the opening and closing parentheses that wrap the rt element that contains the annotation's text.

<rt>	The <rt> HTML element specifies the ruby text component of a ruby annotation, which is used to provide pronunciation, translation, or transliteration information for East Asian typography. The <rt> element must always be contained within a ruby element.

<ruby>	The <ruby> HTML element represents small annotations that are rendered above, below, or next to base text, usually used for showing the pronunciation of East Asian characters. It can also be used for annotating other kinds of text, but this usage is less common.

<s>	The <s> HTML element renders text with a strikethrough, or a line through it. Use the <s> element to represent things that are no longer relevant or no longer accurate. However, <s> is not appropriate when indicating document edits; for that, use the del and ins elements, as appropriate.

<samp>	The <samp> HTML element is used to enclose inline text which represents sample (or quoted) output from a computer program. Its contents are typically rendered using the browser's default monospaced font (such as Courier or Lucida Console).

<small>	The <small> HTML element represents side-comments and small print, like copyright and legal text, independent of its styled presentation. By default, it renders text within it one font-size smaller, such as from small to x-small.

<span>	The <span> HTML element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a div element, but div is a block-level element whereas a <span> is an inline element.

<strong>	The <strong> HTML element indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.

<sub>	The <sub> HTML element specifies inline text which should be displayed as subscript for solely typographical reasons. Subscripts are typically rendered with a lowered baseline using smaller text.

<sup>	The <sup> HTML element specifies inline text which is to be displayed as superscript for solely typographical reasons. Superscripts are usually rendered with a raised baseline using smaller text.

<time>	The <time> HTML element represents a specific period in time. It may include the datetime attribute to translate dates into machine-readable format, allowing for better search engine results or custom features such as reminders.

<u>	The <u> HTML element represents a span of inline text which should be rendered in a way that indicates that it has a non-textual annotation. This is rendered by default as a simple solid underline, but may be altered using CSS.

<var>	The <var> HTML element represents the name of a variable in a mathematical expression or a programming context. It's typically presented using an italicized version of the current typeface, although that behavior is browser-dependent.

<wbr>	The <wbr> HTML element represents a word break opportunity—a position within text where the browser may optionally break a line, though its line-breaking rules would not otherwise create a break at that location.


<!-- IMAGE & MULTIMEDIA -->


## Image & Multimedia
HTML supports various multimedia resources such as images, audio, and video.

<area>	The <area> HTML element defines an area inside an image map that has predefined clickable areas. An image map allows geometric areas on an image to be associated with Hyperlink.

<audio>	The <audio> HTML element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the source element: the browser will choose the most suitable one. It can also be the destination for streamed media, using a MediaStream.

<img>	The <img> HTML element embeds an image into the document.

<map>	The <map> HTML element is used with area elements to define an image map (a clickable link area).

<track>	The <track> HTML element is used as a child of the media elements, audio and video. It lets you specify timed text tracks (or time-based data), for example to automatically handle subtitles. The tracks are formatted in WebVTT format (.vtt files) — Web Video Text Tracks.

<video>	The <video> HTML element embeds a media player which supports video playback into the document. You can use <video> for audio content as well, but the audio element may provide a more appropriate user experience.


<!-- EMBEDDED CONTENT -->
## Embedded content
In addition to regular multimedia content, HTML can include a variety of other content, even if it's not always easy to interact with.

<embed>	The <embed> HTML element embeds external content at the specified point in the document. This content is provided by an external application or other source of interactive content such as a browser plug-in.

<iframe>	The <iframe> HTML element represents a nested browsing context, embedding another HTML page into the current one.

<object>	The <object> HTML element represents an external resource, which can be treated as an image, a nested browsing context, or a resource to be handled by a plugin.

<picture>	The <picture> HTML element contains zero or more source elements and one img element to offer alternative versions of an image for different display/device scenarios.

<portal>	The <portal> HTML element enables the embedding of another HTML page into the current one for the purposes of allowing smoother navigation into new pages.

<source>	The <source> HTML element specifies multiple media resources for the picture, the audio element, or the video element. It is an empty element, meaning that it has no content and does not have a closing tag. It is commonly used to offer the same media content in multiple file formats in order to provide compatibility with a broad range of browsers given their differing support for image file formats and media file formats.



<!-- SVG & MATHML -->


## SVG & MathML
You can embed SVG and MathML content directly into HTML documents, using the <svg> and <math> elements.

<svg>	The svg element is a container that defines a new coordinate system and viewport. It is used as the outermost element of SVG documents, but it can also be used to embed an SVG fragment inside an SVG or HTML document.

<math>	The top-level element in MathML is <math>. Every valid MathML instance must be wrapped in <math> tags. In addition, you must not nest a second <math> element in another, but you can have an arbitrary number of other child elements in it.


<!-- SCRIPTING -->


## Scripting
In order to create dynamic content and Web applications, HTML supports the use of scripting languages, most prominently JavaScript. Certain elements support this capability.

<canvas>	Use the HTML <canvas> element with either the canvas scripting API or the WebGL API to draw graphics and animations.

<noscript>	The <noscript> HTML element defines a section of HTML to be inserted if a script type on the page is unsupported or if scripting is currently turned off in the browser.

<script>	The <script> HTML element is used to embed executable code or data; this is typically used to embed or refer to JavaScript code. The <script> element can also be used with other languages, such as WebGL's GLSL shader programming language and JSON.


<!-- DEMARCATING EDITS -->


## Demarcating edits
These elements let you provide indications that specific parts of the text have been altered.

<del>	The <del> HTML element represents a range of text that has been deleted from a document. This can be used when rendering "track changes" or source code diff information, for example. The ins element can be used for the opposite purpose: to indicate text that has been added to the document.

<ins>	The <ins> HTML element represents a range of text that has been added to a document. You can use the del element to similarly represent a range of text that has been deleted from the document.


<!-- TABLE CONTENT -->


## Table content
The elements here are used to create and handle tabular data.

<caption>	The <caption> HTML element specifies the caption (or title) of a table.

<col>	The <col> HTML element defines a column within a table and is used for defining common semantics on all common cells. It is generally found within a colgroup element.

<colgroup>	The <colgroup> HTML element defines a group of columns within a table.

<table>	The <table> HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

<tbody>	The <tbody> HTML element encapsulates a set of table rows (tr elements), indicating that they comprise the body of the table (table).

<td>	The <td> HTML element defines a cell of a table that contains data. It participates in the table model.

<tfoot>	The <tfoot> HTML element defines a set of rows summarizing the columns of the table.

<th>	The <th> HTML element defines a cell as header of a group of table cells. The exact nature of this group is defined by the scope and headers attributes.

<thead>	The <thead> HTML element defines a set of rows defining the head of the columns of the table.

<tr>	The <tr> HTML element defines a row of cells in a table. The row's cells can then be established using a mix of td (data cell) and th (header cell) elements.


<!-- FORMS -->


## Forms
HTML provides a number of elements which can be used together to create forms which the user can fill out and submit to the Web site or application. There's a great deal of further information about this available in the HTML forms guide.

<button>	The <button> HTML element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs a programmable action, such as submitting a form or opening a dialog.

<datalist>	The <datalist> HTML element contains a set of option elements that represent the permissible or recommended options available to choose from within other controls.

<fieldset>	The <fieldset> HTML element is used to group several controls as well as labels (label) within a web form.

<form>	The <form> HTML element represents a document section containing interactive controls for submitting information.

<input>	The <input> HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The <input> element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.

<label>	The <label> HTML element represents a caption for an item in a user interface.

<legend>	The <legend> HTML element represents a caption for the content of its parent fieldset.

<meter>	The <meter> HTML element represents either a scalar value within a known range or a fractional value.

<optgroup>	The <optgroup> HTML element creates a grouping of options within a select element.

<option>	The <option> HTML element is used to define an item contained in a select, an optgroup, or a datalist element. As such, <option> can represent menu items in popups and other lists of items in an HTML document.

<output>	The <output> HTML element is a container element into which a site or app can inject the results of a calculation or the outcome of a user action.

<progress>	The <progress> HTML element displays an indicator showing the completion progress of a task, typically displayed as a progress bar.

<select>	The <select> HTML element represents a control that provides a menu of options.

<textarea>	The <textarea> HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.


<!-- INTERACTIVE ELEMENTS -->


## Interactive elements
HTML offers a selection of elements which help to create interactive user interface objects.

<details>	The <details> HTML element creates a disclosure widget in which information is visible only when the widget is toggled into an "open" state. A summary or label must be provided using the summary element.

<dialog>	The <dialog> HTML element represents a dialog box or other interactive component, such as a dismissible alert, inspector, or subwindow.

<summary>	The <summary> HTML element specifies a summary, caption, or legend for a details element's disclosure box. Clicking the <summary> element toggles the state of the parent <details> element open and closed.


<!-- WEB COMPONENTS -->


## Web Components
Web Components is an HTML-related technology which makes it possible to, essentially, create and use custom elements as if it were regular HTML. In addition, you can create custom versions of standard HTML elements.

<slot>	The <slot> HTML element—part of the Web Components technology suite—is a placeholder inside a web component that you can fill with your own markup, which lets you create separate DOM trees and present them together.

<template>	The <template> HTML element is a mechanism for holding HTML that is not to be rendered immediately when a page is loaded but may be instantiated subsequently during runtime using JavaScript.


<!-- OBSOLETE & DEPRECATED ELEMENTS -->


## Obsolete and deprecated elements
Warning: These are old HTML elements which are deprecated and should not be used. You should never use them in new projects, and you should replace them in old projects as soon as you can. They are listed here for completeness only.

<acronym>	The <acronym> HTML element allows authors to clearly indicate a sequence of characters that compose an acronym or abbreviation for a word.

<applet>	The obsolete HTML Applet Element (<applet>) embeds a Java applet into the document; this element has been deprecated in favor of object.

<basefont>	The <basefont> HTML element is deprecated. It sets a default font face, size, and color for the other elements which are descended from its parent element. With this set, the font's size can then be varied relative to the base size using the font element.

<bgsound>	The <bgsound> HTML element is deprecated. It sets up a sound file to play in the background while the page is used; use audio instead.

<big>	The <big> HTML deprecated element renders the enclosed text at a font size one level larger than the surrounding text (medium becomes large, for example). The size is capped at the browser's maximum permitted font size.

<blink>	The <blink> HTML element is a non-standard element which causes the enclosed text to flash slowly.

<center>	The <center> HTML element is a block-level element that displays its block-level or inline contents centered horizontally within its containing element. The container is usually, but isn't required to be, body.

<content>	The <content> HTML element—an obsolete part of the Web Components suite of technologies—was used inside of Shadow DOM as an insertion point, and wasn't meant to be used in ordinary HTML. It has now been replaced by the slot element, which creates a point in the DOM at which a shadow DOM can be inserted.

<dir>	The <dir> HTML element is used as a container for a directory of files and/or folders, potentially with styles and icons applied by the user agent. Do not use this obsolete element; instead, you should use the ul element for lists, including lists of files.

<font>	The <font> HTML element defines the font size, color and face for its content.

<frame>	The <frame> HTML element defines a particular area in which another HTML document can be displayed. A frame should be used within a frameset.

<frameset>	The <frameset> HTML element is used to contain frame elements.

<hgroup>	The <hgroup> HTML element represents a multi-level heading for a section of a document. It groups a set of <h1>–<h6> elements.

<image>	The <image> HTML element is an ancient and poorly supported precursor to the img element. It should not be used.

<keygen>	The <keygen> HTML element exists to facilitate generation of key material, and submission of the public key as part of an HTML form. This mechanism is designed for use with Web-based certificate management systems. It is expected that the <keygen> element will be used in an HTML form along with other information needed to construct a certificate request, and that the result of the process will be a signed certificate.

<marquee>	The <marquee> HTML element is used to insert a scrolling area of text. You can control what happens when the text reaches the edges of its content area using its attributes.

<menuitem>	The <menuitem> HTML element represents a command that a user is able to invoke through a popup menu. This includes context menus, as well as menus that might be attached to a menu button.

<nobr>	The <nobr> HTML element prevents the text it contains from automatically wrapping across multiple lines, potentially resulting in the user having to scroll horizontally to see the entire width of the text.

<noembed>	The <noembed> HTML element is an obsolete, non-standard way to provide alternative, or "fallback", content for browsers that do not support the embed element or do not support the type of embedded content an author wishes to use. This element was deprecated in HTML 4.01 and above in favor of placing fallback content between the opening and closing tags of an object element.

<noframes>	The <noframes> HTML element provides content to be presented in browsers that don't support (or have disabled support for) the frame element. Although most commonly-used browsers support frames, there are exceptions, including certain special-use browsers including some mobile browsers, as well as text-mode browsers.

<param>	The <param> HTML element defines parameters for an object element.

<plaintext>	The <plaintext> HTML element renders everything following the start tag as raw text, ignoring any following HTML. There is no closing tag, since everything after it is considered raw text.

<rb>	The <rb> HTML element is used to delimit the base text component of a ruby annotation, i.e. the text that is being annotated. One <rb> element should wrap each separate atomic segment of the base text.

<rtc>	The <rtc> HTML element embraces semantic annotations of characters presented in a ruby of rb elements used inside of ruby element. rb elements can have both pronunciation (rt) and semantic (rtc) annotations.

<shadow>	The <shadow> HTML element—an obsolete part of the Web Components technology suite—was intended to be used as a shadow DOM insertion point. You might have used it if you have created multiple shadow roots under a shadow host. It is not useful in ordinary HTML.

<spacer>	The <spacer> HTML element is an obsolete HTML element which allowed insertion of empty spaces on pages. It was devised by Netscape to accomplish the same effect as a single-pixel layout image, which was something web designers used to use to add white spaces to web pages without actually using an image. However, <spacer> no longer supported by any major browser and the same effects can now be achieved using simple CSS.

<strike>	The <strike> HTML element places a strikethrough (horizontal line) over text.

<tt>	The <tt> HTML element creates inline text which is presented using the user agent default monospace font face. This element was created for the purpose of rendering text as it would be displayed on a fixed-width display such as a teletype, text-only screen, or line printer.

<xmp>	The <xmp> HTML element renders text between the start and end tags without interpreting the HTML in between and using a monospaced font. The HTML2 specification recommended that it should be rendered wide enough to allow 80 characters per line.



<!-- This Markdown Document is intended to use as a HTML FAQ Guide  -->
