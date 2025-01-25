# HTML - Hyper test markup language

-- HTML is the code that is used to structure web page and it's content.
-- The component used to design the structure of websites are called HTML tags.

# HTML tag

-- A container for some content or other HTML tags
-- ex.

`<p> This is paragraph </p>

 ``<p> </p> `` -- this is element 
- content between ``<p> </p>`` called content
``<p>`` -- opening tag
``</p>`` -- closing tag
`` <p> This is paragraph </p> `` -- element

# Basic HTML Page Analysis

``<!DOCTYPE html>   -- tells browser you are using HTML5
<html lang="en">   -- root of HTML document 
<head>             -- container for metadata
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>  -- page title
</head>
<body>   -- contains all data rendered by the browser
    <h1>Hello World</h1>
</body>
</html>``

-- html tag is parent of head and body tag
-- most of the html tag have opening and closing tags with content in between
-- some tags have no content in between ex. <br> -- for next line

# comments in HTML

-- comments are not part of rendering browser.
-- comments are used to reduce comfu 
-- ex. <!--this is body tag -->

## HTML is not case sensitive

ex. 
1. `<p> </P>`
2. `<P> </P>`

# Heading Tags

-- used to display heading in Html
-- search decide on heading

<h1>Hello World!</h1>  --(most important)
<h2>Hello World!</h2>
<h3>Hello World!</h3>
<h4>Hello World!</h4>
<h5>Hello World!</h5>
<h6>Hello World!</h6> ----(least important)

# Paragraphs in HTML

-- used to add paragraph in html.
ex. ``<p>This is sample paragraph</p>``

# Anchor tag

-- used to add link in Html.
-- Attributes

1. href -- source link
2. target -- open link in another tab.


ex.
    1. <a href="https://www.google.com/">google</a>  -- absolute path

    2. <a href="/hello.html">Go to Hello </a> -- realative path

# image tag

-- used add image to your page.

ex.
    <img src="/image.png" alt="NoteBook" height="100">

# Br tag in HTML

-- used add empty line in your page
ex.
<Br>

# Bolt, italic and underline tag

<b>Bold</b>
  
<i>Italic</i>
    
<u>Underlined</u>

# Big and Small tag

- used to display big and small text

ex.

1.  <big>This tag shows big text</big>
   
2.  <small>This tag shows small text</small>

# Hr Tag

- used to display horizontal ruler, used to seperate content

<hr>

# SubScripts and SuperScripts

-- used to write math formula like H20;

# Page Layout Techniques

## semantic

-- Using semantic tag for layout
1. <header></header>
2. <main></mian>  -- main content
3. <footer></footer>

# Inside main tag

1. Section tag

-- used for section on your page

2. Article Tag

-- used for a article on your page.

3. Aside Tag

-- used for content aside main content(ads)


## Non semantic

# Div Tag  -- 

-- Div is a container used for other HTML elements.
-- Block Element (takes full width).
-- By default width of div is zero
--

# Types of element 

1. Block Element

-- Block Element (takes full width)
-List of Block 

<address>             <fieldset>            <nav>
<article>             <figcaption>          <noscript>
<aside>               <figure>              <ol>
<blockquote>          <footer>              <p>
<canvas>              <form>                <pre>
<dd>                  <h1 -- h6>            
<div>                 <header>
<dl>                  <hr>
<dt>                  <li>
                      <main>

2. Inline Element

-- Takes width as per size
-- List of inline tags

<a>             <abbr>              <acronym>
<b>             <bdo>               <big>
<br>            <button>            <cite>
<code>          <dfn>               <em>
<i>             <img>               <input>
<kbd>           <label>             <map>
<object>        <output>
<q>             <samp>              <script>
<select>        <small>             <span>
<strong>        <sub>               <sup>
<textarea>      <time>
<tt><var>



# Span tag

-- Span is also a container used for other HTML element.
-- Span is inline eleement (takes width as per size)








 

