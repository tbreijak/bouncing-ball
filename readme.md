# BouncingBall

### Specs
This daily, ```BouncingBall```, has the following specs:

Create a sketch in which you create an arbitrary number of balls that bounce around the canvas. This should be a familiar problem by now. That said, these have some new and unfamiliar twists:
1. These should be translucent, showing how each ball passes through the other (hint: look at [the p5.js documentation for color](http://p5js.org/reference/#group-Color)).
2. Their positions and directions must be represented by [p5.Vector objects](http://p5js.org/reference/#/p5.Vector).
3. Their direction should be random when they are ```initialize()```ed, but each ball should have the same speed. (A hint: please consult the p5.Vector documentation closely; what functions let you change the direction of a vector?)
4. They should bounce off the edges of the canvas.

### Instructions and hints
1. Fork this repo from the ENG 7006 organization.
2. The included ```sketch.js``` will take care of the basics of creating all the balls and animating them.
3. The code is distributed between ```sketch.js``` and ```bouncing-ball.js```. To get this to spec, specs, you should only need to edit ```bouncing-ball.js```.
4. ```bouncing-ball.js``` contains comments to guide you, but they are relatively minimal. Please write your code from scratch; do not copy-and-paste any code from other sources, although you may use that code to guide you.
