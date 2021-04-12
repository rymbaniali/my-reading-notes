## Read 12 summary :

<canvas> element has only two attributes, width and height and these are both optional, and if we don't use them the canvas will initially be 300 pixels wide and 150 pixels high. Also it can be styled just like any normal image (margin, border, background…).

The <canvas> element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.

There are three functions that draw rectangles on the canvas:

1. fillRect(x, y, width, height) : Draws a filled rectangle.
2. strokeRect(x, y, width, height) : Draws a rectangular outline.
3. clearRect(x, y, width, height) :Clears the specified rectangular area, making it fully transparent.
Each of these three functions takes the same parameters. x and y specify the position on the canvas(relative to the origin) of the top-left corner of the rectangle.

The fillRect() function draws a large black square 100 pixels on each side. The clearRect() function then erases a 60x60 pixel square from the center, and then strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square.

moveTo(x, y) : Moves the pen to the coordinates specified by x and y.
lineTo(x, y) : Draws a line from the current drawing position to the position specified by x and y.
To draw arcs or circles, we use the arc() or arcTo() methods.

to apply styles and colors to the shapes there are two important properties we can use: fillStyle and strokeStyle.

The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw. 
2. strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

Styling text: 
 1. font = value >> The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
2. textAlign = value >> Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
3. textBaseline = value >> Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
4. direction = value >> Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

