# Balls

_**Very Important:**_ _Please do not fork this repository so we can avoid exposing the possible solutions on the web!_

The goal of this fullstack exercise is to get to know how you learn, digest and implement new things. We expect you to write production quality code with today’s CSS and JavaScript standards and clean, object-oriented Ruby code.

![Alt text](example.gif?raw=true "Balls")

## Your task

Create a centered box, with a button labelled "drop". It must be similar to the example gif.
Pressing the button yields the following results:

- If there are no balls in the box it inserts a pink ball.
- Every third ball is a green ball.
- Every fifth ball is a blue ball.
- Every fifteenth ball is a purple ball.
- Every other ball is a pink ball.

The sum shows the number of balls.

The score shows the sum of the balls scores:
- Pink Ball:   1
- Green Ball:  3
- Blue Ball:   5
- Purple Ball: 15

## Constraints

- After the HTML view is loaded with the empty box, JS takes over. No more server rendered HTML or render to html string.
  The rendering of the balls must be in JS. You can't insert an html string sent by the server. You need to dynamically create the balls in JS.
- The drop button fires a JSON request, sends down the number of balls, the backend responds in JSON which ball colour comes next.
- You can't use JS Libraries, no jQuery/Angular/React or any library, just vanilla JS.
- You can't use CSS frameworks, just vanilla CSS/SCSS

## Bonus

- Use es6, and new browser features
