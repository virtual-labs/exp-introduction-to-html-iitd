### 1.1 Introduction

HTML stands for Hyper Text Markup Language, which is the most widely used language on Web to develop web pages. HTML was created by Berners-Lee in late 1991 but "HTML 2.0" was the first standard HTML specification which was published in 1995. HTML 4.01 was a major version of HTML and it was published in late 1999. Though HTML 4.01 version is widely used but currently we are having HTML-5 version which is an extension to HTML 4.01, and this version was published in 2012.

### 1.2 Write code

Web pages can be created and modified by using professional HTML editors. However, for learning HTML we recommend a simple text editor like Notepad or advance text editor like VS Code or Sublime.

Step 1:  Open Notepad in your PC <br>
Step 2:  Write Some HTML Code <br>
Step 3:  Save the HTML Page Name the file 'index.html' and set the encoding to UTF-8 (which is the preferred encoding for HTML files).<br>You can use either .htm or .html as file extension. There is no difference, it is up to you.<br>
Step 4:  View the HTML Page in Your Browser Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose 'Open with').

### 1.3 Structure of an HTML Document

An HTML Document is mainly divided into two parts: 
<br>
<ul>
  <li>HEAD: This contains the information about the HTML document. For Example, Title of the page, version of HTML, Meta Data etc.</li>
   <li>BODY: This contains everything you want to display on the Web Page.</li>
</ul>

```
<!DOCTYPE html>
<html>
    <head>
        <title> Page Title</title>
    </head>
    <body>
    <h2> Write heading here</h2>
    <p> Write paragraph here</p>
    </body>
</html>
```
Every Webpage must contain this code. Below is the complete explanation of each of the tag used in the above piece of HTML code:<br>
<ul>
<li><!DOCTYPE html>: This tag is used to tells the HTML version. This currently tells that the version is HTML 5.</li>
<li><html>: This is called HTML root element and used to wrap all the code.</li>
<li><head>: Head tag contains metadata, title, page CSS etc. All the HTML elements that can be used inside the <head> element are:</li> 
<li><style></li>
<li><title></li>
<li><base></li>
<li><noscript></li>
<li><script></li>
<li><meta></li>
</ul> 

<style>
<title>
<base>
<noscript>
<script>
<meta>
<body>: Body tag is used to enclose all the data which a web page has from texts to links. All the content that you see rendered in the browser is contained within this element. 

### 1.4 Tags
An HTML code that defines every structure on an HTML page, including the placement of text and images and hypertext links. HTML tags begin with the less-than (<) character and end with greater-than (>). These symbols are also called angle brackets.
Heading Tags
Any document starts with a heading. You can use different sizes for your headings. HTML also has six levels of headings, which use the elements h1, h2, h3, h4, h5, and h6. While displaying any heading, browser adds one line before and one line after that heading.

### Description

The HTML ‹h1› tag defines the highest level or most important heading in the HTML document. This tag is also commonly referred to as the ‹h1› element.

The HTML ‹h2› to ‹h6› tags define the different levels of headings in the HTML document.

The HTML ‹b› tag merely gives text a bold appearance but does not provide any semantic meaning to the text. This tag is also commonly referred to as the ‹b› element.

The HTML ‹i› tag merely gives text an italicized appearance but does not provide any semantic meaning to the text. This tag is also commonly referred to as the ‹i› element.

The HTML ‹u› tag defines text that should be styled differently or have a non-textual annotation. Browsers traditionally render the text found within the ‹u› tag as underlined text. This tag is also commonly referred to as the ‹u› element.

The HTML ‹p› tag defines a paragraph in the HTML document. This tag is also commonly referred to as the ‹p› element.

The HTML ‹big› tag makes text one font size bigger in the HTML document. This tag is also commonly referred to as the ‹big› element.

The HTML ‹small› tag makes text one font size smaller in the HTML document. This tag is also commonly referred to as the ‹small› element.
