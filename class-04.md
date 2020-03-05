# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

From the Duckett HTML book:

Chapter 4: Ch.4 “Links” (pp.74-93)
Chapter 15: “Layout” (pp.358-404)
Note: This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364, and look at the code samples on the website that accompanies the textbook. You will have another reading assignment on this chapter, so do not try to digest it all now.

From the Duckett JS book:

Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
Article: “6 Reasons for Pair Programming”

## links
links can link to each other, the same site, open a different browser window, open a new e mail, 
```<a>``` element is used to make links; HREF is the attribute that defines the URL , the text which can be clicked on is inside the tag, need absolute URL when going to a different website

relative URL's point you to somewhere on the same site and do not need an absolute, only in relation to the webpage you are on currently

### directory structure 

important when making URLS both relative and absolute. should reflect relationships between pages and organize. some pages like the homepages are expected to be at the root level like index.html

relative URL's are important so that you note the sub folders in the path

### e-mailing links 

```e-mailto:``` is the first part of an HREF before an e-mail address when defined inside of quotations (see page 85)
target is an attribute that can be used  along with an __ blank to open a web page in a new window.

### linking to a specific part of the same page


if elements have the ID attribute, which could be headers or whatever you can make an HREF which points to their hashtag

### linking to a specific part of another page

you can use a similiar technique if you want to do it on another page, you just need a full URL infront of it

## Layouts

### Key concepts in postitioning elements

as before everything is boxes. It's all about moving, shaping & coloring the boxes. Some things are called containing elements, they are block level that can define width and height, and are different from inline because inline shows as a line of text across the page. 

#### Normal Flow

the positions are static and the do not move. 

#### relative postioning

positions can be percentages, offset or move as the page changes. By page, I mean changing the window of the viewer.

#### absolute postioning

these are items that are taken out of normal flow and are not affected by the positions of other objects. It must be specified where they are by the element they are within.

#### fixed positioning

this is a type of absolute positioning. Relative to the browser window. to use this, the box offset properties are used. (page 368)

#### overlapping elements

all that previous stuff can overlap. if you want to control which elements are on top you can use ```z-index``` property. Its value is a number. the higher the number the closer the element is to the front. 
The ```z-index``` is sometimes called stacking context. 

#### floating elements

Oof! can float right and left, will make things appear as an inline block- but why not be used as an inline block? Have to agree with teacher. 
Can use to put things side by side. more importantly, floats can be cleared to keep them from interfering
Parents of floats elements problem. If an element only contains float elements, some browsers will treat it as it is zero pixels tall. Another reason not to use floats.
Hypothetically, could be fixed with CSS. (page 375) If I ever wanted to do multi column layouts with floats I would look on that page. I'd rather use inline-blocks value for display instead. Many talk poorly of floats.

### screen sizes and resolutions

there are many types of screen sizes and resolutions. You can have coding inside your CSS to detect the screen sizes and apply specific stylings of CSS which would be applicable to the screen it detects. 

#### fixed width layouts

are layouts that don't change size. 

#### liquid layouts 

stretch and contract as user increases or decreases the size of their browser window. Layout tends to use percentages.

#### layout grids

many designers use a grid structure to help them position items on a page. Previous instructors spoke highly of this- it sounds like a good idea.
Woah! 
the number of grid layouts.... Impressive. 
(pg 391 ) discusses CSS frameworks. Seems interesting; will look into further. 


### multiple style sheets

this is the aforementioned multiple CSS to deal with different situations. Can be done with @import_URL ("name of CSS . CSS)
(pg 395) where it discusses multiple style sheets

## function

Covered this in 102 but a function is; function keyword then function name then code block. See example: function sayHello()
{ 
    document.write('Hello!');
}


## Calling function

sayHello();

See 102 learning journal notes. 