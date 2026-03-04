# Exam #2 - Practice A - Objects

- The questions below will help you practice for exam #2
- You should try to write these out on paper first, and then live code the solution to see how close you were
- Concepts covered:
  - looping through an array of object literals and generating HTML
  - creating an object literal
  - creating an ES6 class, and an instance of that class
  - `Object.create()` and the prototype chain

---

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Exam #2 - Practice A</title>
</head>
<body>
<h1>Exam #2 - Practice A</h1>
<ol>
  <!—- The generated HTML will go here -—>
</ol>
<script>
  "use strict";
  
/*
	1) Use a loop (any kind EXCEPT FOR a standard for loop with a counter) to step through the pets array below and put the name and
		the age of each dog in an <li> tag, and then add it to the existing <ol> tag on the page.
	
	The final HTML will look like this after it is added:

	<ol>
		<li>Luna - age 5</li>
		<li>Niko - age 2</li>
	</ol>
*/
 const pets = [{name: "Luna", age: 5}, {name: "Niko", age: 2}];


/*

2) Create a variable called mydog that points at an object literal, give the object name and age properties with values of “Rover” and 2 respectively.
Define an ageUp() method for this object that will cause the object’s age property to increase by 1.

*/


/*
	3) Create an ES6 class named Dog. 

	3A) In the constructor of Dog initialize the 2 passed in arguments -
	`name` and `age` - as properties.

	3B) Give the Dog class a `bark()` method, when called this method will log out 
	"Woof, Woof my name is XXX" where XXX is the value of the `.name` property of the dog instance

	4) Create a new instance of Dog named `dog1`. Pass in "Wags" and 5 for the name and age.
	4A) Write code that calls the `bark` method of `dog1` 
	
	5) Create a new object literal named `fancyDog` and set its prototype object to dog1 above.
	Hint: Use Object.create()
	5A) Add a `breed` property to `fancyDog` and give it a value of "Bichon Frisé"
	5B) Call the `bark` method of `fancyDog` - it should log out "Woof, Woof my name is Wags"

*/


/*
6) Object methods - know about what these methods do and how to use them.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object

- Object.create() - used above - can be used to create inheritance hierarchies
- Object.keys() - we only used this once, it returns an array of an object's keys (aka properties)
- Object.seal() - you should know this one
- Object.freeze() - you should know this one
- Object.assign() - used to copy properties from one object to another

*/

  
	
  </script>


</body>
</html>
```
