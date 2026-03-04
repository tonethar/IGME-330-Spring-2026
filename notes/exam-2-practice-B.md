# Exam #2 - Practice B - Canvas

- The questions below will help you practice for exam #2
- You should try to write these out on paper first, and then live code the solution to see how close you were
- Concepts covered:
  - canvas that we saw on exam #1
  - drawing a rotated object in the canvas - hint: you will also need `.translate()`
  - creating a canvas helper function

<hr>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Exam #2 - Practice B</title>
  <style>
    canvas {
		  border: 1px solid black;
    }
  </style>
</head>
<body>
<h1>Exam #2 - Practice B</h1>
<canvas width="400" height="300"></canvas>
<script>
  "use strict";
  
  const ctx = document.querySelector("canvas").getContext("2d");
  
  // Exam #1 questions (you should still know how to do for exam #2)
 
  // 1 - Write canvas code that will draw a 10-pixel wide green line from (200,200) to (200,400)

  // 2 - Write canvas code that will fill a 50-pixel radius circle with a solid red color. The circle is centered at (100,100)

	/*
	3 - Without using fillRect(), draw a 30 x 30 pixel square at (100,100), stroke the outside of the square with a
    5-pixel wide yellow stroke, and fill the square with a solid red color
	*/
   

   // Here are some new canvas questions
	 
	/*
	4 - Using fillRect(), draw a 30 x 30 pixel square at (100,100).
	Fill the square with a solid red color, and rotate it 45 degrees to the right on its center axis.
	
	
	5 - Implement the following helper function. Don't forget about our best
	practice of using save() and restore()
	
	const drawCircle = (ctx,x,y,radius,fillStyle,scaleX,scaleY) => {
		// YOU WRITE THE REST
	};
	*/

	/*
	6) Other canvas stuff:
	- Canvas gives us a way to change how different layers of graphics interact with the .globalCompositeOperation property
    - Be sure you understand how ctx.save() and ctx.restore() work with drawing state properties and with the
      Current Transformation Matrix (see the Translate/Rotate/Scale assignment)
	*/
  </script>


</body>
</html>
```
