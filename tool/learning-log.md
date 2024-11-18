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

* I was tinkering with the pong game, the output is interactive. I moved my cursor up and down on the screen, and the barriers would move up and down. The pong ball would come from the middle of the output and it would count by 1's by how many times the ball hit the barriers.

* I tried out the platformer tutorial, and it was really fun. I use the arrow buttons to move the "Bean" sprite left and right. And I use the space button to jump. I changed the duration time of how long you stay big after eating the apple.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
