# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)


ssorted bits of documentation:

> Read [this article](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) on the Chart.js API.

> Chart.js docs: You’ll be needing these!

> Read the following articles on the Canvas API.

> [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
> [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
> [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
> [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)


* There is a chart.js which we can have access through via using it's url as a source for script and this is known as using a third part library, basically it is using code which isn't yours to accomplish a task, this javascript in particular is useful for drawing charts via the canvas tag

* this particular third party javascript library uses oobjects which have arrays of other objects to while using respect type and understanding how deeply nested within the arrays the item is will help minimize issues

[This is their Demo](https://www.webdesignerdepot.com/cdn-origin/uploads7/easily-create-stunning-animated-charts-with-chart-js/chartjs-demo.html)

* canvas is like an image element that can be drawn on, the articles says it requires a closing tag

* rendering context are done via ```.getContext('2d')``` on a variable which targeted a canvas element's id to find it, or potential a created canvas a variable, you assign the result of using the method on a variable and then can use that as a variable within functions which draw in canvas with methods which were made in the third party library

* Example: (cxt is the context)
> function draw() {
>   var canvas = document.getElementById('canvas');
>  if (canvas.getContext) {
>    var ctx = canvas.getContext('2d');
>
>    ctx.fillRect(25, 25, 100, 100);
>    ctx.clearRect(45, 45, 60, 60);
>    ctx.strokeRect(50, 50, 50, 50);
>  }
>}

#### Drawing

* List of different methods for drawing paths: ```beginPath(), closePath(), stroke(), fill()```

* The page lists many many explicit examples

* 2d objects allow caching of draw commands

#### Color
* Color code example: ```fillStyle = color, strokeStyle = color```

* THE Color grigs on this page are pretty, the fill makes color filled in blocks, the stroke make the lines of the shape the colors, even allowing color gradiants over a series of different shapes within the canvas if you have Math() to alter the calculation of the rgb values, allowing color to be dynamic, or even animated

* transparancy is possible via using the alpha channel of rgba and hsla, and likewise can be mathmatically or procedurally altered

* Line style list: ```lineWidth = value, lineCap = type, lineJoin = type, miterLimit = value, getLineDash(), setLineDash(segments), lineDashOffset = value```

* Sub values list (unsorted): ```butt, round, square, round, bevel, miter```

#### Patterns
* code is ```createPattern(image, type)```
    *Example String Values which may be used in the type parameter: ```repeat, repeat-x, repeat-y, no-repeat```

#### Shadows
* Shadows are what you think they are and they have these properties: ```shadowOffsetX = float, shadowOffsetY = float, shadowBlur = float, shadowColor = color```

* You can make Fill Rules while using ```fill``` (or ```clip``` or ```isPointinPath```) which are an algorithm which allow you to determin if a point is inside or outside a path and thus know which side of the path to fill 