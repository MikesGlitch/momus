# Momus
User feedback tool for web apps.


Example:
To beat: https://www.userback.io/demo-video

Maybe try to MAKE some of the component pieces rather than use HTML to canvas etc to keep the lib small.  There's gotta be an easy way to do it. Like just saving image as pdf or something.

Canvas drawing: https://konvajs.org/docs/sandbox/index.html

HTML to canvas: https://html2canvas.hertzen.com 

https://github.com/niklasvh/html2canvas

Dom to jpeg - Seems to do the same as HTML to Canvas but is smaller: https://github.com/tsayen/dom-to-image

Thoughts: Could convert the HTML to canvas and then draw on it, then export to JPEG or whatever.  Would probably be a large library if I did that.  Would be a big bundle.  


Another thought:  Just a Canvas Drawing lib with a full height and width to same size as the webpage.  Keep it transparent (if possible) then allow drawing over it.  Then see if there's a way to merge the HTML with the Canvas and save it to JPEG.
