---
title: Setting Up a Game Project
authors: Jon Stapleton
video: https://www.youtube.com/embed/14I8C6FKINQ
description: Learn how to create a blank game project that uses p5js and the p5play library. This tutorial explains how the "setup" and "draw" functions work, how to test your program, how the p5js coordinate system works, and how to save your work.
type: tutorial
---
:::quick-take{src="TODO: hosted example" link}
Games made with p5js require at least two ***functions***: the `setup()` function, and the `draw()` function. 

- The computer performs the instructions written in `setup()` *once* at the beginning of the program. Your `setup()` function must contain a `new Canvas(width, height)` or a `createCanvas(width, height)` command to set the size of the game window.
- After running the `setup()` code, the computer begins running the instructions written in `draw()` *over and over again*, repeating the instructions until you click the "stop" button

Check out the example for a basic, blank program.
:::
