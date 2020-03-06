# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)


### Images!

* the fun part which adds a lot of aethetic appeal!
* these majorly affect design: they should be well placed, relevant, well styled
* ```<img attribute="value"></img>```
* ```<img scr="https://pale-crusader.github.io/guessing-game/image/familyflag.jpg" alt="What displays if broken or blocked"></img>"``` 
* already had above image on my guessing game page 
* defaults as a inline element, keep in mind if you want to center to css display:block or display:inline-block with left and right margis to auto
* can control width, height, border, border-radius
* if you place inside a line of text it can appear odd, see page 102 in HTML book for picture of how odd and why
* OLD CODE ```align``` is an Attribute which has the values ```left``` and ```right``` again this better shown than described,  see page 104 in HTML book for picture. When aligned it allows other elements to flow to the other side. **MUCH BETTER THAN TRYING TO FLOAT IT! _WISH I COULD USE THIS INSTEAD OF FLOAT FOR LEFT AND RIGHT IMAGES!_**
* OH NO!! Align is no longer used in HTML5
* Three rules for using Images
    * Save in appropriate format for purpose, website consistency, loading speed and sharpness are considerations when picking format
    * save images at correct size _(ninimizes need for using Styling to correct later)_
    * Measure images in Pixels, they are a true measurement
* Adobe photoshop is a professional tool (photoshop elements is cheaper), MSpaint, Paint.net and GIMP are FREE alternatives I use


#### Image Formats 
* jpg is good for images with MANY colors that are subtle, and no transparency
* GIF and PNG are good for images with few colors, or has transparecy, sky and grass are not flat colors, they are subtle 

#### Image Dimensions
* save at the height and width you intend to display as
* cropping can cause loss of important 
* really basic image editting stuff, msPaint level stuff about croppin and resizing
* resays use pixels as size measurement
* vector images are made in advanced programs and adjust their resolution for their display size
* animated gif, can make in GIMP, making a loading circle is an example of good use
* tranparency if straight edge use gif, if curved or diagnonal png
* check existing image sizes if replacing on existing site
* ```<figure>``` and ```<figcaption>``` are formaking an image which is a figure and its caption
* see page 120

### Color

* veryimportant aethetically and to themes, motifs and overall design
* skipping typing notes to part I haven't been doing
* opacity this involves alpha channel in rgba and hsla, have not played with those yet

### Text

* those that directly let you control font (bold, italics, regular)
* those that affect all text no matter font (color, spacing)
* typeface terminology: Serif (extra details at ends of strokes), san-serif (without serif, ie straight un embellished strokes), monospace (each character same width as every other character),weight (light,medium, bold, black), style (normal, italic(cursive like), obliqe{aka angled normal}), strtch(condensed, regular extended)

Extra Font information, ESPECIALLY LICENSING Page 27

* font CSS options listed
* Page 275 & 276 Font scales with examples and charts

* different browser support different fonts the chart for that is on page 278
    * Bad news is on chart no format is supported by all browsers, ttf/otf is closest missing only of the two oldest browsers
* basic Word Processing Font Formatting with previous terminology to know what to look up like font-weight ect
*  Drop Shadow makes it appear like the text is droping a shadow and looks neat, see page 288
* You can target the first letter and first line see page 289
