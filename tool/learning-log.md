# Tool Learning Log

## Tool: **[Kaboom.js](https://kaboomjs.com/)**

## Project: **What I learned when using this tool**

---

### 10/19/24: LL1

[Installation](https://kaboomjs.com/doc/setup)

* The installation feature of this tool is the easiest way to get started by using the [CLI Tool](https://www.npmjs.com/package/create-kaboom).

```JS
$ npm init kaboom -- mygame
$ cd mygame
$ npm run dev
```

* The CLI Tool will use the directory `mygame` to preview the game.

    * You can see your changes when you edit `src/main.js` and refresh the page.

* Another quick and easy way to use Kaboom is getting a package by using a CDN provider.

    * CPN providers include `unpkg`, `skypack`, and `jsdelivr`. It's where the Kaboom package is available after it's deployed to npm

* It's easier to get other packages and use version control using Node.js and npm.

```JS
$ npm install kaboom
```

* Using Kaboom with NPM requires `esbuild`, `webpack`, `parcel`, and `vitejs`.

### 10/27/24: LL2

* Using kaboom.js, I ran the code for a custom component tutorial, and it made the output "get funky" by pressing the space bar

* When I changed the `Let isFunky` to `true` and ran the code, the 'Bean' went funky by itself without pressing any buttons

* When I changed `Let isFunky` back to `false` and ran the code, the 'Bean' was back to normal and I pressed the space bar to make it "get funky"

### 11/15/24: LL3

* I was running a test code in the Kaboom.js playground, and when I pressed "Run" on the code, the sprite "Bean" stayed in the same spot on the output, while the ghost sprites moved to different spots.

* "Bean" spins staying in place  when `anchor()` is `center`. I changed `anchor()` to `left` or `right`, "Bean" would spin out of place.

* I changed the number on `player.angle += 120 * dt()` from 120 to higher  and lower numbers. When the number was greater, "Bean" would spin faster. When the number was smaller, "Bean" would spin slower.

### 11/18/24: LL4

* I tried different tutorials on the Kaboom.js playground. I tinkered with maze, platforming, and pong.

* I was tinkering with the [pong](https://kaboomjs.com/play?example=pong) game, the output is interactive. I moved my cursor up and down on the screen, and the barriers would move up and down. The pong ball would come from the middle of the output and it would count by 1's by how many times the ball hit the barriers.

* I tried out the [platformer](https://kaboomjs.com/play?example=platformer) tutorial, and it was really fun. I use the arrow buttons to move the "Bean" sprite left and right. And I use the space button to jump. I changed the duration time of how long you stay big after eating the apple.

### 12/2/24 LL5

* I tinkered with the draw, rpg, and concert tutorials on the Kaboom.js playground.

* In the [draw](https://kaboomjs.com/play?example=draw) tutorial, when I hovered my cursor on the output, the cursor would show a black line trace in the motion of my cursor. When I pressed the button on the mouse and held it, I could use it to draw and leave the motion strokes.

* In the [concert](https://kaboomjs.com/play?example=concert) tutorial, I used the arrow keys to move "Bean" left and right, and the space bar to jump. I made Bean jump using the space bar to hit colorful musical note blocks that would let out their own jingle. When Bean hits the red block, the output shakes and zooms in on Bean, then I have to run the code over again.

* In the [rpg](https://kaboomjs.com/play?example=rpg) tutorial, Bean and friends are trapped in rooms and Bean needs to collect the key to unlock the door to escape the room. Bean's friends are there to help Bean get out. I used the arrow keys to move, when Bean goes to a friend, it shows a helpful message from the friend. When Bean collects the key, Bean can open the door and go to the next level.

### 12/16/24 LL6

* I tinkered with the [ai](https://kaboomjs.com/play?example=ai) tutorial. In this tutorial, I used the arrow keys to move Bean around the output screen, and Ghosty follows him. At a certain point, Ghosty stops and shoots a bullet at Bean where he stops. When Bean gets shot, he disappears with a "Kaboom".

* I tinkered with the [flappy](https://kaboomjs.com/play?example=flappy) tutorial. In this tutorial, Bean has to go through the holes between the blue blocks. To make him flap, I can press the space bar or click on the output screen with my mouse cursor. When Bean goes through the blue blocks, it counts how many times I went through the blue blocks.

* I tinkered with the [tween](https://kaboomjs.com/play?example=tween) tutorial. In this tutorial, when I used my cursor and clicked on the output screen, Bean would move in the direction and position of my cursor. I also used the arrow keys to change the text in upper left corner: `linear`, `easeInSine`, `easeOutSine`, `easeInOutSine`, `easeInQuad`, `easeOutQuad`, `easeInOutQuad`, `easeInCubic`, `easeOutCubic`, `easeInOutCubic`, etc.

### 1/6/25 LL7

* I tinkered with the [scenes](https://kaboomjs.com/play?example=scenes) tutorial. This is like the platforming tutorial, but things are very different. In this tutorial, you move Bean across the blocks, collect the coins, go through the portals, and avoid the danger. When you collect 3 coins, you clear the level. Unlike the plaforming game, you have to go through all 3 parts of the level. You use the arrow keys to move, and the space bar to jump. Avoid the spikes and voids.

* I tinkered with the [eatlove](https://kaboomjs.com/play?example=eatlove) tutorial. In this tutorial, you use your cursor to move Bean around the output screen. He has to only eat the hearts. When Bean eats the hearts, a "Kaboom" appears and makes a vibrating affect to the screen. When Bean eats the watermelons, grapes, apples, and pineapples, you lose and you have to start over.

* I thinkered with the [flamebar](https://kaboomjs.com/play?example=flamebar) tutorial. In this tutorial, you use the arrow keys to move Bean around the screen, but he has to avoid touching the "flamebars", which are made out of pineapples. When Bean touches the "flamebars", he disappears in a "Kaboom".

### 1/14/25 LL8

* I tinkered with the [egg](https://kaboomjs.com/play?example=egg) tutorial. This tutorial is Bean laying eggs! The eggs will appear in Bean's previous spot and Bean will move to a different spot when you press the space bar. And there's a score counter at the top left, but usually you don't see it do anything.

* I tinkered with the [hover](https://kaboomjs.com/play?example=hover) tutorial. This tutorial allows the user to hover the cursor over Bean and he changes colors. He starts off as a different color other than his original color. The first one only changes from red to green. The second one automatically changes from red to green to blue when the cursor stays on it.

I tinkered with the [postEffect](https://kaboomjs.com/play?example=postEffect) tutorial. This tutorial is also like the platforming tutorial, except that you can make the graphics look different by pressing the up and down arrow keys.

### 2/24/25 LL9

* Now that I've tried many different types of codes for my freedom project, my next step is to put them into action. I need to see how they really run so my freedom project is fully and correctly interactive, as it will be used by other people.

* I can use the [dialog](https://kaboomjs.com/play?example=dialog) feature for when there's new players. I can make the dialog sound like a greeting to new players, telling them the controls, the purpose of the game, and how to play the game.

* I will use the [platformer](https://kaboomjs.com/play?example=platformer) feature to make the game. Levels of different types of seasons and worlds.

### 3/10/25 MAR10 Day LL10

* I tinkered with the platformer tutorial, and changed a few things, to determine how my freedom project code will run. I changed the duration of the apple's enlarge affect.

* I will make sure I make my freedom project look different than the tutorial on Kaboom. I will make changes to the code so it won't look like I plagiarized.

* I will make this project look like a deluxe version of the tutorial. I will make my own code to make it look newly made and more enjoyable when other people see and use my project.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
