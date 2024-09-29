---
title: Sprite Basics
authors: Jon Stapleton
description: Learn how to initialize and modify the attributes of `Sprite` objects. This tutorial covers the `new Sprite()` and `new Sprite(x,y)` constructors, the distinction between primitive variables and objects, and assigning values to `Sprite` attributes.
type: tutorial
video: https://www.youtube.com/embed/14I8C6FKINQ
---
:::quick-take
Sprites are ***objects*** that represent the different elements of your game. You will need to create a Sprite for each item, character, or landscape element. To make a basic sprite, initialize a variable using a name of your choice, then use the `new Sprite()` ***constructor*** as shown.

```javascript{#example}
let spr // change the name if you want!

function setup() {
	new Canvas(200,200)
	spr = new Sprite()
	spr.diameter = 30
	spr.x = 100
	spr.y = 100
}

function draw() {
	background(255)
}
```

By default, Sprites will be squares. You can change the size of a square Sprite by setting its `width` and `height` ***attributes***. If you set the `diameter` attribute, the Sprite will be displayed as a circle.

To set the location of the Sprite in the game window, assign values to the `x` and `y` attributes as shown.

You do not need to write a command to tell the computer to display the sprite like you would with a shape; the computer displays all Sprites automatically by default in the order you created them.
:::