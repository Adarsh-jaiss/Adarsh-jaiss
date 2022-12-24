# Simple HTML tags
There are many tags available in HTML. Here you will learn about common tags that you'll use as a developer.

###  Headings
Headings allow you to display titles and subtitles on your webpage.

```
<body>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
</body>

```
The following displays in the web browser:

``` Heading style displayed in browser
Paragraphs
Paragraphs contain text content. 

```


### <p>
  
   This paragraph
   contains a lot of lines
   but they are ignored.
  
</p>
The following displays in the web browser: 

Paragraph style displayed in browser 
Note that putting content on a new line is ignored by the web browser.


### Line Breaks
As you've learned, line breaks in the paragraph tag line are ignored by HTML. Instead, they must be specified using the <br> tag. The <br> tag does not need a closing tag.

```
<p>
   This paragraph<br>
   contains a lot of lines<br>
   and they are displayed.
</p>
```

The following displays in the web browser: 

Line breaks displayed in browser 


### Strong

Strong tags can be used to indicate that a range of text has importance.

```
<p>
   No matter how much the dog barks: <strong>don't feed him chocolate</strong>.
</p>
```
The following displays in the web browser: 

Text with strong tag displayed in browser 


### Bold
Bold tags can be used to draw the reader's attention to a range of text.

```
<p>
   The primary colors are <b>red</b>, <b>yellow</b> and <b>blue</b>.
</p>
```
The following displays in the web browser: 

Bold text displayed in browser 
The following displays in the web browser: 

Text with strong tag displayed in browser 
Bold tags should be used to draw attention but not to indicate that something is more important. Consider the following example:
```
The three core technologies of the Internet are <b>HTML</b>, <b>CSS</b> and <b>Javascript</b>.
```
The following displays in the web browser: 

Bold text displayed in browser 

### Emphasis
Emphasis tags can be used to add emphasis to text.

```
<p>
   Wake up <em>now</em>!
</p>

```
The following displays in the web browser: 

Text with emphasis tag displayed in browser 

### Italics
Italics tags can be used to offset a range of text.

```
<p>
   The term <i>HTML</i> stands for HyperText Markup Language.
</p>
```
The following displays in the web browser: 

Italic text displayed in browser 

### Emphasis vs. Italics
By default both tags will have the same visual effect in the web browser. The only difference is the meaning.

Emphasis tags stress the text contained in them. Let's explore the following example:

```
I <em>really</em> want ice cream.
```
The following displays in the web browser: 

Text with emphasis tag displayed in browser. 
Italics represent off-set text and should be used for technical terms, titles, a thought or a phrase from another language, for example:

```
My favourite book is <i>Dracula</i>.
```
The following displays in the web browser: 

Italic text displayed in browser
Screen readers will not announce any difference if an italics tag is used.

### Lists
You can add lists to your web pages. There are two types of lists in HTML.

Lists can be unordered using the <ul> tag. List items are specified using the <li> tag, for example:

```
<ul>
   <li>Tea</li>
   <li>Sugar</li>
   <li>Milk</li>
</ul>
```
This displays in the web browser as:

Bullet style displayed in the browser img10
Lists can also be ordered using the <ol> tag. Again, list items are specified using the <li> tag.

```
<ol>
   <li>Rocky</li>
   <li>Rocky II</li>
   <li>Rocky III</li>
</ol>
```
This displays as the following in the web browser.

Numbered list style displayed in browser img11

### Div Tags
A <div> tag defines a content division in a HTML document. It acts as a generic container and has no effect on the content unless it is styled by CSS.

The following example shows a <div> element that contains a paragraph element:

```
<div>
   <p>This is a paragraph inside a div</p>
</div>
  

It can be nested inside other elements, for example:

```
<div>
   <div>
      <p>This is a paragraph inside a div that’s inside another div</p>
   </div>
</div>
```
Div inside a dive displayed in browser 
As mentioned, the div has no impact on content unless it is styled by CSS. Let’s add a small CSS rule that styles all divs on the page.

Don't worry about the meaning of the CSS just yet, you'll explore CSS further in a later lesson. In summary, you're applying a rule that adds a border and some visual spacing to the element.

```
<style>
   div {
      border: 1px solid black;
      padding: 2px;
   }
</style>
<div>
   <div>
      <p>This is a paragraph inside stylized divs</p>
   </div>
```

Div elements are an important part of building webpages. More advanced usage of div elements will be explored in another course.

### Comments
If you want to leave a comment in the code for other developers, it can be added as:

<!-- This is a comment --> 

The comment will not be displayed in the web browser.
### Anchor tag <a> </a>

  - It is used to link different websites or images
  
  ```
  <a href(hypertext reference) = "" > Descriptive name</a>
  ```  
  
 ### Forms
  
  ![image](https://user-images.githubusercontent.com/96974600/209425406-b762ee67-5961-4917-8c83-6384af548b24.png)
![image](https://user-images.githubusercontent.com/96974600/209425462-9b454c5b-fc25-4fcb-a508-b734001d995b.png)

