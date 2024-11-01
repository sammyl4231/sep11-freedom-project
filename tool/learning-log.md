# Tool Learning Log

## Tool: **[Kaboom.js](https://kaboomjs.com/)**

## Project: **What I learned when using this tool**

---

### 10/19/24:
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

### 10/27/24:
* Using kaboom.js, I ran the code for a custom component tutorial, and it made the output "get funky" by pressing the space bar

* When I changed the `Let isFunky` to `true` and ran the code, the 'Bean' went funky by itself without pressing any buttons

* When I changed `Let isFunky` back to `false` and ran the code, the 'Bean' was back to normal and I pressed the space bar to make it "get funky"


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
