### 1.1 Introduction

HTML stands for Hyper Text Markup Language, which is the most widely used language on web to develop web pages. HTML was created by Berners-Lee in late 1991 but "HTML 2.0" was the first standard HTML specification which was published in 1995. HTML 4.01 was a major version of HTML and it was published in late 1999. Though HTML 4.01 version is widely used but currently we are having HTML-5 version which is an extension to HTML 4.01, and this version was published in 2012.

### 1.2 Write code

Web pages can be created and modified by using professional HTML editors. However, for learning HTML we recommend a simple text editor like Notepad or advance text editor like VS Code or Sublime.

**Step 1:**  Open Sublime text editor in your PC. <br>
**Step 2:**  Write some HTML code. <br>
**Step 3:**  Save the HTML page with name 'index.html'.<br>You can use either .htm or .html as file extension. There is no difference, it is up to you.<br>
**Step 4:**  View the HTML page in your browser by opening the saved HTML file in your favorite browser (double click on the file, or right-click - and choose 'Open with').

### 1.3 Structure of an HTML Document

An HTML document is mainly divided into two parts: 
<br>

- **HEAD:** This contains the information about the HTML document. For Example, Title of the page, Version of HTML, Meta Data etc.
- **BODY:** This contains everything you want to display on the Web Page.


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
Every webpage must contain this code. Below is the complete explanation of each of the tag used in the above piece of HTML code:<br>

- **&lt;!DOCTYPE html&gt;:** This tag is used to tells the HTML version. This currently tells that the version is HTML 5.
- **&lt;html&gt;:** This is called HTML root element and used to wrap all the code.
- **&lt;head&gt;:** Head tag contains metadata, title, page CSS etc.
- **&lt;body&gt;:** Body tag is used to enclose all the data which a web page has from texts to links. All the content that you see rendered in the browser is contained within this element.


### 1.4 Tags
An HTML code that defines every structure on an HTML page, including the placement of text, images and hypertext links. HTML tags begin with the less-than (<) character and end with greater-than (>). These symbols are also called angle brackets.<br>Most of the tags in HTML are used in pair like starting and closing tag but Empty tags are used individually which means only starting tag can be used for empty tags. No closing tag is requred for using empty tags.

#### 1.4.1 Heading Tags:
Any document starts with a heading. You can use different sizes for your headings. HTML also has six levels of headings, which use the elements h1, h2, h3, h4, h5, and h6. While displaying any heading, browser adds one line before and one line after that heading.


- The HTML ‹h1› tag defines the highest level or most important heading in the HTML document. This tag is also commonly referred to as the ‹h1› element.

- The HTML ‹h2› to ‹h6› tags define the different levels of headings in the HTML document.


 ##### Syntax of Heading Tags:
 
 ```  
<h1>Heading 1 </h1> 
<h2>Heading 2 </h2>
<h3>Heading 3 </h3>
<h4>Heading 4 </h4>
<h5>Heading 5 </h5>
<h6>Heading 6 </h6>
```

#### 1.4.2 Other Tags:

- The HTML **‹b› tag** merely gives text a bold appearance but does not provide any semantic meaning to the text. This tag is also commonly referred to as the **‹b›** element.

```
 syntax:
 <b>Write your text here to make it Bold</b>
 ```
- The HTML **‹i› tag** merely gives text an italicized appearance but does not provide any semantic meaning to the text. This tag is also commonly referred to as the **‹i›** element.

```
 syntax:
 <i>Write your text here to make it Italic</i>
 ```
- The HTML **‹u› tag** defines text that should be styled differently or have a non-textual annotation. Browsers traditionally render the text found within the **‹u›** tag as underlined text. This tag is also commonly referred to as the ‹u› element.

```
 syntax:
 <u>Write your text here to make it underlined</u>
 ```
- The HTML **‹p› tag** defines a paragraph in the HTML document. This tag is also commonly referred to as the **‹p›** element.

```
 syntax:
 <p>Write your paragraph here</p>
 ```
- The HTML **‹big› tag** makes text one font size bigger in the HTML document. This tag is also commonly referred to as the **‹big›** element.

```
 syntax:
 <big>Write your text here</big>
 ```
- The HTML **‹small› tag** makes text one font size smaller in the HTML document. This tag is also commonly referred to as the **‹small›** element.

```
 syntax:
 <small>Write your text here</small>
 ```

