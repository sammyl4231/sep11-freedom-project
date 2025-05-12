# Presentation Plan

## Hook
* I will introduce my project with a question about if they ever wondered how a platforming game is made works. Something like this: "Have any of you ever wondered how platforming games work and/or are made?"

## Product
* I could include a screenshot of my project

## Process
* To make this project I used [Kaboom.js](https://kaboomjs.com/play?example=platformer). I've tried so many different types of codes to make things like platforming, pong, rpg, draw, concert, flappy, egg, and lots more. I used almost everything I learned throughout the year to make this game work.

For example, how I'll make the enemies move:
```JS
function patrol(speed = 60, dir = 1) {
        return {
            id: "patrol",
            require: [ "pos", "area" ],
            add() {
                this.on("collide", (obj, col) => {
                    if (col.isLeft() || col.isRight()) {
                        dir = -dir
                    }
                })
            },
            update() {
                this.move(speed * dir, 0)
            },
        }
    }
```

## Conclusion
* [Sammy's Platforming Game](https://sammyl4231.github.io/sep11-freedom-project/)

**Takeaways:**

* using symbols like "@", ">", "^", "$", "%", "#" can be used to format the levels and how they would look

* `go()` determines when the player wins or loses the game

* `play()` makes specific parts of the game make their specific sound, whenever the player touches the enemy(ies), loses, wins, collects the coins, jumps, etc

<!-- EXAMPLE

## Hook
* Verbal riddle of GGD

## Product
* GIF/Demo of example/non-example

## Process
* Flowchart of plan
  * MVP: noun -> door -> yes/no
  * Beyond MVP: noun -> word relation API -> noun API -> yes/no, with counterexample
* Code snippets of:
  * MVP
  * Both APIs
  * Challenge with API keys

## Conclusion
* [URL to project]
* Takeaways
  * Less = more: the heart of the riddle was one line of code; it obviously took more to make the entire thing work, but one complicated line of regular expressions was essentially the solution to the riddle
  * Expect the unexpected: it’s important to budget time for things you don’t account for; for example, I didn’t consider the fact that I would need another entire API to detect nouns
  * Determination is key: ironically enough, I had to make my API keys private. At first, it didn’t seem like it was possible, which meant I couldn’t publish my app. But after all of that hard work, I was determined to find a solution, and I found it in config variables.
* "Presentation can’t, but a speech can"


-->
