# Reading 1

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

## HTML
* Hyper Text Markup Language
* Defines the structure of the webpage
* Similar to other document structures, with different area serving purposes
* Uses Elements which are defined by tags which are containers or boxes
* there are opening and closing tags
* Attributes give extra details about elements (like the source or language)
* Body is where the pages content 
* Head is where the the meta data stored
* View Source via right clicking


* DOCTYPES says what version the HTML is being used

* press Ctrl + ```/```
* id singles out a solitary element
* class marks a group of elements
* ```<hl>```, ```<p>```, ```<ul>```, ```<l1>``` are block elements
* ```<<a>```, ```<b>```, ```<em>```, and ```<img>``` are inline elements
* ```<iframe>``` is a window into the page to another page

* ```<header>``` is top of page
* ```<footer>``` is bottom of page
* ```<nav>``` is where block of navigation links of page are
* ```<article>``` is place which could be stand alone published document
* ```<aside>``` is related to article when within an ```<article>``` and about page when not
* ```<section>``` is groups related content
* ```<hgroups>``` is bgroups various levels of headings
* ```<figures>``` is images or videos related to article
* ```<figcaption>``` is is text for images or videos related to article
* ```<div>``` is division when others are not applicable

### Turning entire block element into links!

* nesting the block element within an ```<a></a>```

Older browser help CSS

```header, section, footer, aside, nav, article, figure, figcaption {display: block;
}```

or this Javascript

```<!--[if lt IE 9]>
<script scr="http://html5shiv.googlecode/svn/trunk/html.js>
<![endif]-->```


