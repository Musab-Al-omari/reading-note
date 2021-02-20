# Chapter 16: “Images” 

`<img>`To add an image into the page you need to use an `<img>` element. This is an empty
element (which means there is no closing tag). It must carry the
following two attributes:
1. `src`
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
2. `alt`
This provides a text description
of the image which describes the
image if you cannot see it.
3. `title`
You can also use the title
attribute with the `<img>` element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a too tip when the
user hovers over the image.

## Controlling sizes of images
You can control the size of an image using the **width** and
**height** properties in CSS, just like you can for any other box.
```
img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;}
```




## Aligning images 
There are two ways that
this is commonly achieved:

1. The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.
```

img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}
```
## Centering images
there are
two common ways in which you
can horizontally center an image:
1. On the containing element,
you can use the text-align
property with a value of center.
2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.
```
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}

```




# Chapter 19: “Practical Information”
Search Engine Optimization 'SEO'
it help you understand the key concepts so you can improve your website's visibility on search engines.



1. On-Page Techniques
* Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <title> element which lives
inside the <head> element.
* URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.
* Headings
If the keywords are in a heading
<hn> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text. 

* Text

Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.
* Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").
* Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.
* Page Descriptions
The description also lives inside
the `<head>` element and is
specified using a `<meta>` tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)
