# Docs for the HTML < canvas> Element & Chart.js Summary

**Charts :**

Charts are far better for displaying data visually.


**charts steps** 

* First thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
* Write a script that will retrieve the context of the canvas.
* Inside the same script tags, we need to create our data, an object that contains labels for the base of our chart and datasets to describe the values on the chart.
* Move to the pie chart and write canvas element.
* Next, we need to create the data. supply a value and a color for each section.
* After the pieData we’ll add our options.
* Finally, let’s add a bar chart to our page by adding the canvas element.
* Next, we retrieve the element and create the graph.
* And finally, we add in the bar chart’s data 
...........................................
>>>>



## Basic usage of canvas:

**Canvas element:**

* It looks like the < img> element except it doesn’t have src and alt.
>
* It is similar to img with ( margin / border / background..  ) but different with (< video>, < audio>, or < picture> elements).
>
* It has only height and width. When you don’t add height and width, it will take 300 pixels wide and 150 pixels high.
>
* It requires the closing tag (</ canvas>).Drawing shapes with canvas:
>
* We will be using a canvas grid or coordinate space.

It only supports two primitive shapes: rectangles and paths.
>
* other shapes must be created by combining one or more paths.fillRect(x, y, width, height).


![](https://mk0wittysparksm75pi6.kinstacdn.com/wp-content/uploads/2017/07/HTML-Canvas-Cheatsheet.png)



**Draws a filled rectangle.**


* strokeRect(x, y, width, height)
* Draws a rectangular outline.
* clearRect(x, y, width, height)
* Clears the specified rectangular area, making it fully transparent.

**Drawing paths:**

* First, you create the path.
>
* Then you use drawing commands to draw into the path.
>
* Once the path has been created, you can stroke or fill the path to render it.


**Functions for drawing paths :**

* beginPath() / Creates a new path.
* Path methods / Methods to set different  paths for objects.
* closePath() / Adds a straight line to the path, going to the start of the current sub-path.
* stroke() / Draws the shape by stroking its outline.
* fill() / Draws a solid shape by filling the path's content area.


**Applying styles and colors :**



* use: fillStyle and stroke style.
* fillStyle = color
* Sets the style used when filling shapes.
* stroke style = color
* Sets the style for shapes' outlines.globalAlpha = transparency value
* Applies the specified transparency value to all future shapes drawn on the canvas.


**Drawing text:**

* fillText(text, x, y [, maxWidth])
>
* Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
>
* strokeText(text, x, y [, maxWidth])
>
* Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


**Styling text:**

* font = value
* The current text style is used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
* textAlign = value
* Text alignment setting. Possible values: start, end, left, right, or center. The default value is started.
* textBaseline = value
* Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
* direction = value
* Directionality. Possible values: ltr, rtl, inherit. The default value is inherit. 


![](https://miro.medium.com/max/3524/1*72II7JJoLugWTsztSaBN8w.png)

