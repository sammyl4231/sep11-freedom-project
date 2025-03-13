# Entry 4
##### 3/13/25

### Content

Lately I've been learning my source/tool [Kaboom.js](https://kaboomjs.com/) in many other different ways. I've been tinkering with different types of tutorials like sound and control tutorials. I haven't started coding my Freedom Project yet, nor have I made any progress towards my MVP, but I will be soon.

Control code of [platforming](https://kaboomjs.com/play?example=platformer):                                          
```JS
// custom component controlling enemy patrol movement
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

How the [platforming](https://kaboomjs.com/play?example=platformer) levels will be made:
```JS
const LEVELS = [
	[
		"    0       ",
		"   --       ",
		"       $$   ",
		" %    ===   ",
		"            ",
		"   ^^  > = @",
		"============",
	],
	[
		"                          $",
		"                          $",
		"                          $",
		"                          $",
		"                          $",
		"           $$         =   $",
		"  %      ====         =   $",
		"                      =   $",
		"                      =    ",
		"       ^^      = >    =   @",
		"===========================",
	],
	[
		"     $    $    $    $     $",
		"     $    $    $    $     $",
		"                           ",
		"                           ",
		"                           ",
		"                           ",
		"                           ",
		" ^^^^>^^^^>^^^^>^^^^>^^^^^@",
		"===========================",
	],
]
```

### Engineering Design Process (EDP)

The stage I'm currently in of EDP is Broinstorm possible solutions and Plan the most Promising Solution. Considering I haven't started my Freedom Project yet, I will think about how to set up my code as a starter for the project. And maybe I'll think about what the project will look like when I start coding, and how it'll run when I put it into action.

### Skills

The skills I'm using currently using right now are Problem Decompostion, Attention to Detail, Consideration, and Creativity. I'm braeking down my task into bits when I can make which part of my Freedom Project on a certain day or point in time. I want to make the code look neat and correct without any bugs or debugging. I'm aware that other people will see my freedom project and use it when it's done. I want to be creative with my code and make it look vibrant and colorful, and controllable in any way possible.
