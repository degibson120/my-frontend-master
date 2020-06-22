## Frontend Masters Bootcamp

## intro to course

- `reading`
- `set up and prereqs - bootcamp`
- `add extention`
- `HTML - ul, ol, li, h1, p, br, blockquote, img,`
- `W3school exercise2-5,headings, paragraphs1-3, comments, links1-3 & 5, images(1, 3, 5, 6), lists1-2`
- `created an about page - paragraph w/info about me. paragraph what I'd like in web dev`
- `made list 3 things about me.favorite quote, pic of me, link to feq visited site`

# Introduction to the Course

- `checked email and joined for bootcamp on Slack`
- `posted a message with my name, location and said hi in the bootcamp-live channel`
- `looked around, followed some interesting links, checked out a few students web pages they built in first course`

# Setup & Prerequisites (already installed)

- `install vsc`
  - `install-browser-extention2.0.0(functionality)`
  - `reload to activate`

# HTML

- `created index.html, used the "!" symbol along with the "tab" button to automatically generate foundation tags for html document`
- `identifed and explained meaning of each HTML tags in basic html document and how they have opening and ending < >`
  - `<DOCTYPE>, <html></html>, <head></head>, <meta charset=" ">, <meta name=" ">, <title></title>, <body></body>`
- `introduces <p></p> tags to assign text areas as paragraphs`
- `introduces <h1></h1> tags to assign heading`
- `introduces <ul></ul> tags to assign a unordered list`
- `introduces <li></li> tags to assign list items`
- `created hobbies.html, added simular content(text & tags)`
- `toggle word wrap up in "View" on the VSC menu bar`

# Review

# quiz of HTML terminology

- `What is HTML = Hyper Text Markup Language`
- `What is a tag = identifies portions of document`
- `What is <!DOCTYPE> = indicating the document type is often HTML5`
- `What is head and body do../ body = actually displays things onto page itself/ head = contains meta and title`
- `What is element do = simular as a tag`
- `What is an attribute = additional discriptions in that tag`

# images best practices on how to insert images into a web page.

- `<img> tag walk through`
- `applied <img> tag to index.html, included alt text and title text, added title atribute which allows the description text to show when mouse hovers over image in browser`
- `image formats include:`
  `JPG, GIF, PNG = RASTER IMAGES (a bunch of pixels)`
  `SVG = vector image (a mathmatical equation)`
  `alt = displays if the image does not. Read by search engines & screen readers. alt text should fully desribe the image, so you couls imagine what the image looked like if you could not see it`
  `dont add images in large size to web page- resize in an editor`
- `downloading & adding an image:`
  `added img tag with link to local/downloaded img file located in project folder`
- `Blockquote= <blockquote>, strong= <str> and emphisis= <em>, and citation= <cite> tags>`

  - `Markup Validation Service`
    `copied and checked my code in validator`
    `had one issue of missing closing bracket on </strong> tag`

# book markup excercise

- `marked up given text from book`
  `only a few errors. Basic ones that were likely caused by my poor typing habits of looking as keyboard and not screen`

## HTML summarized:

- `<p> paragraph`
- `<h1> is biggest`
- `<h6> is the smallest`
- `<br> line break`
- `<blockquote> for long quotes`
- `<cite> citing someone's work/belongs to`
- `<a> link = href`
- `<img> alt = picture description`
- `<ul> unordered list`
- `<ol> ordered list`
- `<li> list items`
- `<strong> strong emphasis - bold`
- `<em> emphasis`
- `<div> container`
- `<section> container that has related information`
- `<article> Stand alone content.`
- `<nav> navigation bar container`

# CSS

## hamburger css

header {
border-bottom: 4px solid #9EA9C1;
}
main {
border-top: 2px solid #dddddd;
margin-top: 0.5rem;
}
nav ul {
list-style: none;
margin: 0;
}
nav a {
display: block;
padding: .75rem;
text-decoration: none;
}
`------------`
html {
box-sizing: border-box;
}
_, _::before, _::after {
box-sizing: inherit;
}
body {
font-family: "Open Sans", Arial, Helvetica, sans-serif;
margin: 1rem;
}
header, h1, h2, h3, h4, h5, h6 {
font-family: Nobile, Arial, Helvetica, sans-serif;
font-weight: 500;
}
section > h1 {
color: #9EA9C1;
}
/_ header styles \*/
header {
font-weight: 400;
}
header h1 {
margin: 0;
font-weight: 400;
color: #C85028;
}
header h2 {
font-weight: 400;
}

/_ article styles _/
article {
border-bottom: 4px solid #3c2b67;
padding-bottom: 2rem;
}
img, .floatleft, .floatright {
display: block;
margin: 1rem auto 0 auto;
max-width: 100%;
}
a {
color: #C85028;
font-weight: bold;
text-decoration: none;
}
a:hover {
color: #7E64BE;
}
/_ dev styling _/
#devs img {
display: inline;
max-width: 125px;
}
#devs figure {
margin: 0;
padding: 0;
}
/_ resources styling _/
#resources {
background-color: #f1f1f1;
padding: 1rem;
}
#resources h1 {
color: #000;
margin-top: 0;
}
#resources h1 small {
font-weight: 400;
}
#resources ul {
padding: 0;
margin: 0;
list-style-type: none;
}
#resources li {
border-bottom: 1px solid #ccc;
display: block;
}
#resources a {
display: block;
color: #3c2b67;
text-decoration: none;
padding: 0.5rem;
}
#resources a:hover {
color: #6a7a9f;
}
#devs ul {
list-style-type: none;
padding: 0;
margin: 0;
}
`---------------`

## CSS CALC() and custom properties

# Layout

# Forms

# GitHub

- `github setup`
- `created frontend repository`
- `cloned it to my desktop app`
- `git commit - A "commit" is the moment you upload these files and folders to GitHub.`
- `danielle was here testing,...again,..this is it!`
- `commit to master-published a branch`

# Calculator HTML & CSS Exercise

# Programming Fundamentals

# Functions and Scope

# Exercise: Quiz

# Objects and Arrays

# Exercise: Make the Tests Pass

# The DOM

# Exercise: Making the Calculator Work with JavaScript

# Making Your Site Interactive

# AJAX

# Exercise: Dog App

# Exercise: Feed-A-Star-Mole
