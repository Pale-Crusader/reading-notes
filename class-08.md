# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)

## HTML/CSS Book
## Chapter 15

### CSS
* Pages 358
* Key Concept is Building Blocks/Boxes
* Containing Elements

#### Positioning

* Normal Flow
    * the positions are static and the do not move. 
    * ```position:static```
* relative postioning
    * positions can be percentages, offset or move as the page changes. By page, I mean changing the window of the viewer.
    * ```position:relative```
* absolute postioning
    * these are items that are taken out of normal flow and are not affected by the positions of other objects. It must be specified where they are by the element they are within.
    * ```position:absolute```
* fixed positioning
    * this is a type of absolute positioning. Relative to the browser window. to use this, the box offset properties are used. (page 368) 
    * ```position:fixed```
* floating elements
    * can float right and left, will make things appear to flow
    * issues of floats: if an element only contain floated element some browsers treat as 0 pixel tall
    * this could be fixed via added empty html element sibling(old method), or purely CSS application to fix

* ```clear:``` this property allows you to declare nothing should touch the ```value``` side.
    * ```left``` 
    * ```right``` 
    * ```both``` 
    * ```none``` 

        * overlapping elements (all that previous stuff can overlap. if you want to control which elements are on top you can use ```z-index``` property. Its value is a number. the higher the number the closer the element is to the front. 
        The ```z-index``` is sometimes called stacking context. 

* screen sizes & resolution
    * screens and resolution vary greatly
    * Page sizes often designed around 960-1000 pixels to deal with larger size displays
    * fixed width layouts do not change
        * specify ```width``` with pixels
    * liquid layouts and stretched and contract to fit the display
        * specify ```width``` with percentages
    * layout grids
        * visual arts often use a grid to organize arrangements

[layout notes image](https://pale-crusader.github.io/reading-notes/img/layout-notes.png "This is the image on the page for my reference") 
