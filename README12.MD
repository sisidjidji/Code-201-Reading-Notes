# CLASS-12

# 1. The <canvas> element:

At first sight a **< canvas>** looks like the **< img>** element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the **< canvas>** element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

# 2.Drawing rectangles

Unlike SVG, **< canvas>** only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

First let's look at the rectangle. There are three functions that draw rectangles on the canvas:

fillRect(x, y, width, height)
Draws a filled rectangle.

strokeRect(x, y, width, height)
Draws a rectangular outline.

clearRect(x, y, width, height)

Clears the specified rectangular area, making it fully transparent.

Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.


# 3.Colors:

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

Sets the style used when filling shapes.

strokeStyle = color

Sets the style for shapes' outlines.

color is a string representing a CSS < color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).


# 4.Drawing text:

The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.