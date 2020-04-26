# game-of-lifeish
While wanting to put Conway's Game of Life as a header to my personal website, I stumbled upon other nice patters that can nicely produce "pixel art".
Use at own desire and tweak at own please. It is not optimised by any means for peformance. Code has also not been normalised.

## Setup
Include a Canvas with the desired width/height in the html
`<canvas id="pixelPattern" width="800" height="150"></canvas>`

There is no templating/data connection in this setup from Javascript to Canvas, so one has to manually modify width and height on both HTML tag and Javascript code

## Increase / Decrease

If you want a larger/smaller amount of pixels, increase width height on both javascript/html.
If you want larger rectangles to be filled, tweak in the fillRect / clearRect the width and height.
Keep in might that you need to keep the proportions across the 2 of them.

### Demo
![Pixel propagation](gameofLifeish.gif)

Nevertheless, as this came from the idea to reproduce the Game of Life as a tribute, R.I.P John Horton Conway!
