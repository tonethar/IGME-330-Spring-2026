# Week 5A - Practice Quiz

## More Canvas review questions

- For the following questions, you can assume that a `ctx` variable exists and that is pointing at a `CanvasRenderingContext2D` instance

1 - In order for the user to actually see a canvas *path* you will need to ________________ and/or ________________ it.

```


```

2 - What are the default values for `ctx.strokeStyle`, `ctx.fillStyle` and `ctx.lineWidth` if your code does not otherwise specify them?

```


```

3 - What is the default `height` and `width` of the `<canvas>` tag if you don’t specify a value (use google or the Web Inspector to find out)

```


```

4 - In the canvas coordinate system, where is `(0,0)` located?


```


```

5 - List 3 rectangle convenience methods (ones where you don't have to separately specify a *path*)


```


```

6 - Where is the default "anchor point" of a *rectangle* draw in canvas (center of rectangle, or upper-left, etc)

```


```

7 - Write code (without resorting to a canvas *convenience method*) that will *fill* a green 100x100 rectangle located at x=200, y=50

```



```

8 - Write code that will put a red 10-pixel *stroke* around a circle (of 50-pixel radius) that is located at `(320,240)`

```




```

9 - Where is the default "anchor point" of a *circle* draw in canvas (center, or upper-left, etc)

```


```

10 - Are `arc()` angle values specified in *degrees* or *radians*?

```


```

11 - By default, which way is the `arc()` drawn, *clockwise* or *counter-clockwise*?

```


```

12 - Write code that will draw a 5-pixel wide purple line from `(100,100)` to `(640,480)`

```


```

13 - A path "ends" when you call `closePath()` or ________________

```


```

---

**5A-quiz-start.html**

```js
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<title>Random Canvas Stuff</title>
	<style>
	canvas{
		border:1px solid gray;
	}
	</style>
	<script>
		"use strict";
		
		const init = () => {
			let canvas = document.querySelector("canvas");
			let ctx = canvas.getContext("2d");
			ctx.fillStyle = "salmon"; 
			ctx.fillRect(20,20,600,440); 

			
			
		};
		
		window.onload = init;
	</script>
</head>
<body>
	<canvas width="640" height="480">
		Get a real browser!
	</canvas>
</body>
</html>
```
