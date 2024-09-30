---
title: Calling Methods
authors: Jon Stapleton
description: Learn how to call functions and methods in Javascript. This tutorial covers reading library documentation, calling methods, and passing arguments.
type: tutorial
---
:::quick-take
***Functions*** are instructions that tell the computer to do something. There are two basic ways you'll encounter functions when making games with p5js:

Function ***definitions*** are named blocks of code. You need to create function definitions for the `setup()` and `draw()` functions so the computer knows where your code is. Function definitions look like this:

```javascript
function setup() {
	// your code goes here
}
```

You ***call*** functions when you use any of the p5js or p5play library commands. For example, you might call the `createCanvas(200, 200)` function to tell the computer to make a game window, and the `circle` function to tell the computer to display a circle:

```javascript
function setup() {
	createCanvas(200,200)
	circle(100, 100, 50)
}
```

The numbers in the parentheses are called ***arguments***. They control *how* the computer follows the command. Every function has its own arguments that control a different thing about the command.
:::