---
title: Variables & Data Types
authors: Jon Stapleton
description: Learn how to have the computer initialize, modify, and read the values of `number` and `String` variables. This tutorial covers the `=` assignment operator, the `let` keyword, and the difference between objects like Sprites and primitive variables
type: tutorial
---
:::quick-take
***Variables*** are like containers that the computer uses to store information. The computer can set the value of a variable using the assignment operator (`=`) and then use the variable in place of a number or `String` somewhere in the program (rather than using a ***literal*** value).

:::p5sketch
```javascript
let x = 100
let message = "Hello!"
function setup() {
	createCanvas(200,200)
}
function draw() {
	background(255)
	circle(x, 100, 50)
	text(message, 100, 100)
}
```
:::

Variables are useful because they allow you to give a piece of data a *name* in your program. This can help make it easier to read your code, plus it allows the computer to *change* the value of the variable over the course of the program's runtime. Read more about that in the [[manipulating-variables|tutorial about manipulating variables]].ds
:::