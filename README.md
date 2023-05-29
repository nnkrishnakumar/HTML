# HTML
Notes of html and contents:

Lecture_1: Introduction of HTML :
---------------------------------
>   what is HTML?
Ans> HTML is a way of displaying Web pages with text and images or multimedia content.HTML is not a programming language, but a markup language. An HTML file is a text file containing small markup tags. The markup tags tell the web browser, such as Mozila Firefox or Google Chrome, how to display the page. An HTML file must have an htm or html file extension. HTML stands for HyperText Markup Language.

2> Html pages are of two types:
    > Static Pages- Static Pages, as the name indicates, comparise static content(text or images).So you can only see the contents of a web page without being able to have any interaction with it.

    > Dynamic pages: Dynamic pages are those where the content of the web page depend on user input. So interaction with the user is required in order to display the webb page.For example. consider a web page which requires a number to be entered from the user in order to find out if it is enven or odd. When then user enters the number and clicks on the appropriate button, the number is sent to the web server, which in turn returns the result to the user in an HTML page.
----------------------------------------------------------
Lecture:3
----------
Tags: A tag os a bit of text that acts as a point demarcation.To creat a tag, HTML gives certain characters special meaning: the angle brackets <and>.

    Putting characters within angle brackets creates a tag.
<h1>A heading</h1>

There are two tags:
--------------------
start tags or opening tag and End tag or closing tag. An end tags always matches the start tag always matches a start tag, except that it has an extra forward slash after the opening angle bracket.

<h1>A heading</h1>

Element:
---------
The combination of s start and end tags define an element. Everything between the two tags is referreed to as the contents of the element.
<h1>A heading</h1>

---------------------------------------------------------------------------------------------------
Lecture: 4:
------------
Attributes provide additional information about the contents of an element. They apprear on the opening tag of the element and are made up of two parts: - a name and a value, separated by an equals sign.

<p lang="en-us">Paragraph in English</p>  == it is called elments.  
  Paragraph in English==> it is called content.
  lang = it is attribute name
  "en-us" = it is attribute value
  <p lang="en-us"> = it is opening tag 
  </p> =it is called closing tag  

The attribute name indicates what kind of extra infromation you are supplying about the element's content.It should be written in lowercase. 

The attribute name indicates what kind of extra information you are supplying about the element's content.It should be written in lowercase.

The value is the information or setting for the attribute.It should be placed in double quotes.Different attributes can have different values.

In this example an attribute called lang is ysed to indicate the language use in this element. The value of this attribute on this page specifies it is in US English.

Note: HTML5 allows you to use uppercase attribute names and omit the quote marks, but this is not recommended.
------------------------------------------------------------------------------------------------------------
Lecture:5: HTML tag
----------
<HTML> is a starting tag. To delimit the text inside, add a closing tag by adding a forward slash "/" to the starting tag. Most but not all tags have a closing tag. It is necessary to write the code for an HTML page 
between <HTML> and </HTML>. This <HTML> tells the browser is "this is the start of an HTML doctument" and 
</HTML> "this is the end of an HTML documents".

<HTML> </HTML>
-------------------------------------------------------------------------------------------------------
Lecture:6:
----------
Before the <body> element you will often see a <head> element. This contains information about the page, rather than information that is shown within the main part of the browser. You will usually find a <title>
element inside the <head> element.<head> is opening head tag and </head> is closing head tag.
<html>
    <head>
        <title>Hello</title>
    </head>
</html>
---------------------------------------------------------------------------------------------------------
Lecture:7: Title tag:
---------------------
The contents of the <title> element are either shown in the top of the browser above where you usually type in the URL of the page you want to visit, or on the tab for that page(if your browser uses tabs to allow you to view multiple pages at the same time). <title> is opening title tag and</title> closing title tag.

<html> 
    <head>
        <title>Hello</title>
    </head>
</html>
----------------------------------------------------------------------------------------------------
Lecture:8:Body tag:
--------------------
Everything inside this elements is shown inside the main browser window.
<body> is opening body tag and </body> is closing tag.
<html>
    <head>
        <title> Hello </title>
    </head>
    <body>
        <h1>Body of page</h1>
    </body>
</html>
-----------------------------------------------------------------------------------------
Lecture:10: Type of tags:
--------------------------
1> Container Tag: Which has opening and closing tag.
Ex: 
    <html> ...</html>
    <head> ...</head>
    <body> ...</body>

2> Empty Tag: which has only opening tag.
Ex: 
<br>
<area>
<base>
<hr>
<img>
<input>
-----------------------------------------------------------------------------------------------------------
Lecture:11: Version of HTML:

Version             Year
HTML                1991
HTML 2.0            1995
HTML 3.2            1997
HTML 4.01           1999
XHTML               2000
HTML5               2014

HTML 4.01:
-----------
HTML 4.01 Strict:
<!DOCTYPE HTML PUBLIC> "-//W3C//DTD HTML 4.01//EN"
"http://www.w3.org/TR/html4/strict.dtd">

HTML 4.01 Transitional
<!DOCTYPE HTML PUBLIC> "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">

HTML 4.01 Frameset
<!DOCTYPE HTML PUBLIC> "-//W3C//DTD HTML 4.01 Frameset//EN"
"http://www.w3.org/TR/html4/Frameset.dtd">

----------------------------------------------------------------------------------------------------------------------------------------
Lecture:12: Introduction of HTML5:
----------------------------------
HTML 5 enables to create more interactive websites by embedding audio video and graphics on the web page.

The purpose of HTML5 is primarily to make it easier for web developers.
New Features:
    - Browser Support
    - Geolocation
    - Offline Application Cache
    - Web Storage
    - Error Handling 
    - New Application Programming Interface(API)
    - New Structure

----------------------------------------------------------------------------------------------------------------------------------
Lecture 13: Feature of HTML5:
-----------------------------
New Features:
    - Browser Support
    - Geolocation
    - Offline Application Cache
    - Web Storage
    - Error Handling 
    - New Application Programming Interface(API)
    - New Structure

***************************************************(Incomplete)*******************************************

------------------------------------------------------------------------------------------------------------------------------
Lecture:14:HTML 5 doctype declaration:
-------------------------------------
<!DOCTYPE html>
> it is an instruction to the web browser about what version of HTML the page is written in.
> The <!DOCTYPE> declaration is not case sensitive.
----------------------------------------------------------------------------------------------------------------------------------
Lecture:15: How to create Plain text web page in HTML5:
--------------------------------------------------------


--------------------------------------------------------------------------------------------------------------
Lecture:16: how to insert new line or line break using br tag:
-------------------------------------------------------------
1> <br> or <br/> both are similar 
The <br> tag in the HTML code insert a line break in the text

2> if i need two empty line then use <br><br> twice and so on 

----------------------------------------------------------------------------------------------------------
Lecture17: how to write headings using h tag in HTML
----------------------------------------------------
Heading defines the structure and formate of a document. There are six heading tag:-
<h1>...</h1>   --> largest heading tag
<h2>...</h2>
<h3>...</h3>
<h4>...</h4>
<h5>...</h5>
<h6>...</h6>   --> smallest heading tag
Any text inside these tags is displayed differntly depending on the heading number.

2> heading get their own line on the web pages by starting from a new line.
----------------------------------------------------------------------------------------------------------
Lecture:18: Pragragh tag:
------------------------
The <p> tag is used to create new pargraph on web page. It has a closing tag</p> which is optional beacuse a paragraph automatically ends when we start another paragraph.

<p>...</p>

Note: - 
--------
--> Number of line in paragraph depends on the size of web browser window.
--> if we resize the browser window, the number of lines in this paragraph will change.

--------------------------------------------------------------------------------------------------------
Lecture:19: subscript and Superscript using sub and sup Tag in HTML
-------------------------------------------------------------------
> Subscript:
------------
> A subscropt is a text that appears smaller than a regular text.
> The <sub>....</sub> tag is used to create a subscript on a web page.

> SuperScript:
--------------
A Superscript is a text taht apprears smaller size above the regular text.
The <sup>....</sup> tag is used to create a Superscript on a web page.

-----------------------------------------------------------------------------------------------------------
Lecture:20: Horizontal Rule or Horizontal line using hr tag in HTML:
----------------------------------------------------------------------
> The <hr> tag is used to create a horizontal rule on the web page.
> it is an empty tag.
> The web browser starts a horizontal rule from a new line, and any text that follow this tag is also display in a new line.

exmaple: horizontal_tag.html
--------------------------------------------------------------------------------------------------------
Lecture:21: Align--> it is an attribute.
----------------------------------------
> Center--> Aligns the whole text to the center of the web page align="center"
> Left--> Aligns the whole text to the left side of the web page align="left"
> Right--> Aligns the whole text to the right side of the web page align="right"
> Justify--> Justifies the whole text and also indentes the first line align ="justify"

> Align attribute used with text kinds of tag like 
eg.
* With Heading
<h1 align="right">...</h1>

*With Paragraph
<p align="right">...</p>

* with horizontal Rule:
<hr align="right">

sheet example: align_attributes.html
--------------------------------------------------------------------------------------------------------
Lecture: 22: Bold tag using html:
---------------------------------
The <b>...</b> tag is used to render the text in bold style.

example_Sheet: bold.html
-------------------------------------------------------------------------------------------------------
Lecture:23: italic tag:
----------------------
the <i>...</i> tag is used to render the text into italic from.

example_sheet: italic_tag.html