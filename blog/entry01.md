# Entry 1
##### 10/29/24

### Content

The tool I decided to use for my Freedom Project is [Kaboom.js](https://kaboomjs.com/). I will use it to make a platforming game. When I first tinkered with it, I changed the code in a custom component turtorial, when the output was "get funky". One of the code lines was `Let isFunky`, it was originally false. The output said "Press Space to get funky". It worked when I did it. When I changed `Let isFunky` to true, the code ran by itself without pressing any keys.

### Engineering Design Process

My current stage in the EDP is Define the Problem. Kaboom.js doesn't have as many tutorials to try out myself, but I did test out a tutorial I found, the [component demo](https://kaboomjs.com/play?example=component). I was very unsure how to use it or what to do with it. All I did was edit a line of the code and run it, and a minor different output happened. I changed the code from `Let isFunky = false` to `Let isFunky = true`.

```JS
// Custom component

kaboom()

loadSprite("bean", "/sprites/bean.png")

// Components are just functions that returns an object that follows a certain format
function funky() {

	// Can use local closed variables to store component state
	let isFunky = false
```

[Next](entry02.md)

[Home](../README.md)
