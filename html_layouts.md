# HTML Layouts


Websites often display content in multiple columns (like a magazine or newspaper).



## HTML Layout Using <div> Elements



This example uses four <div> elements to create a multiple column layout:

**Example**
```
<body>

<div id="header">
<h1>City Gallery</h1>
</div>

<div id="nav">
London<br>
Paris<br>
Tokyo
</div>

<div id="section">
<h1>London</h1>
<p>London is the capital city of England. It is the most populous city in the United Kingdom,
with a metropolitan area of over 13 million inhabitants.</p>
<p>Standing on the River Thames, London has been a major settlement for two millennia,
its history going back to its founding by the Romans, who named it Londinium.</p>
</div>

<div id="footer">
Copyright © opteamize.in
</div>

</body>```

**The CSS:**
```
<style>
#header {
    background-color:black;
    color:white;
    text-align:center;
    padding:5px;
}
#nav {
    line-height:30px;
    background-color:#eeeeee;
    height:300px;
    width:100px;
    float:left;
    padding:5px; 
}
#section {
    width:350px;
    float:left;
    padding:10px; 
}
#footer {
    background-color:black;
    color:white;
    clear:both;
    text-align:center;
    padding:5px; 
}
</style>```

## Website Layout Using HTML5


HTML5 offers new semantic elements that define different parts of a web page:

![HTML5 Semantic Elements	](img_sem_elements.gif)
* ```<header>``` - Defines a header for a document or a section
* ```<nav>``` - Defines a container for navigation links
* ```<section>``` - Defines a section in a document
* ```<article>``` - Defines an independent self-contained article
* ```<aside>``` - Defines content aside from the content (like a sidebar)
* ```<footer>``` - Defines a footer for a document or a section
* ```<details>``` - Defines additional details
* ```<summary>``` - Defines a heading for the ```<details>``` element

This example uses ```<header>```, ```<nav>```, ```<section>```, and ```<footer>``` to create a multiple column layout:

**Example**
```
<body>

<header>
<h1>City Gallery</h1>
</header>

<nav>
London<br>
Paris<br>
Tokyo
</nav>

<section>
<h1>London</h1>
<p>London is the capital city of England. It is the most populous city in the United Kingdom,
with a metropolitan area of over 13 million inhabitants.</p>
<p>Standing on the River Thames, London has been a major settlement for two millennia,
its history going back to its founding by the Romans, who named it Londinium.</p>
</section>

<footer>
Copyright © opteamize.in
</footer>

</body>```

**The CSS:**
```
<style>
header {
    background-color:black;
    color:white;
    text-align:center;
    padding:5px; 
}
nav {
    line-height:30px;
    background-color:#eeeeee;
    height:300px;
    width:100px;
    float:left;
    padding:5px; 
}
section {
    width:350px;
    float:left;
    padding:10px; 
}
footer {
    background-color:black;
    color:white;
    clear:both;
    text-align:center;
    padding:5px; 
}
</style>```

## HTML Layout Using Tables


Layout can be achieved using the <table> element, because table elements can be styled with CSS:

**Example**
```
<body>

<table class="lamp">
<tr>
  <th>
    <img src="/images/lamp.jpg" alt="Note" style="height:32px;width:32px">
  </th>
  <td>
    The table element was not designed to be a layout tool.
  </td>
</tr>
</table>

</body>```


**The CSS:**
```
<style>
table.lamp {
    width:100%;
    border:1px solid #d4d4d4;
}
table.lamp th, td {
    padding:10px;
}
table.lamp th {
    width:40px;
}
</style>```