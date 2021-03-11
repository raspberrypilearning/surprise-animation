## Setup

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1">
Have you got an idea about your animation? In this step, add a backdrop, main character and interesting object. 
</div>
<div>  
![Dinosaur surprise in the setup state](images/dinosaur-surprise.png)
</div>
</div>

--- task ---

Open a [new Scratch project](https://scratch.mit.edu/projects/editor){:target=”_blank”} to look at the range of sprites and backdrops. Spend some time thinking about your main character, interesting object and backdrop.

--- /task ---

--- task ---

Choose a sprite for your main character and another sprite to be the interesting object.

![Chose a sprite button](images/add-sprite.png)

You can create a character from shapes using the rectangle and oval tools in the paint editor. 

[[[scratch3-backdrops-and-sprites-using-shapes]]]

Don't add eyes yet because they need to be separate sprites.

![Pig costume created using the paint editor](images/pig-costume.png)


--- /task ---

Where do you want your animation to take place?

--- task ---

**Choose** a backdrop to set the scene. 

![Chose a backdrop button](images/add-backdrop.png)

--- /task ---

Where do you want your sprites to start? How big will they be? How should they look?

--- task ---

Add a `when flag clicked`{:class="block3events"} block then underneath add blocks to setup your sprites at the beginning of your animation. 

Remember to set up both your main character and your interesting object.

--- collapse ---

---
title: Position your sprites
---

To change the position of your sprite for the whole project, move your main character to a good position on the Stage. 

To change the position of your sprite for part of the project, move your main character to a good position on the Stage then add a `go to x y`{:class="block3motion"} block to your code.

```blocks3
go to x: (0) y: (0) // with your coordinates
```

Repeat this task for your interesting object. 

--- /collapse ---

--- collapse ---

---
title: Resize your sprites
---

To change the size of your sprite for the whole project, change the size property in the Sprite pane:

![sprite size changed from 100 to 50](images/sprite-pane-size.png)

To change the size of your sprite for part of the project, add code to `set size to`{:class="block3looks"} the size you want. This option is good if you want your sprite to change size in the project. 

```blocks3
set size to [100] % // <100 smaller, >100 bigger
```

--- /collapse ---

--- collapse ---

---
title: Set costume of your sprite
---

To change the costume of your sprite for the whole project, click on the Costumes tab and select one of the available costumes. 

![costumes in the costumes tab](images/nano-costumes.png)

To change the costume of your sprite for part of the project, add a `switch costume to`{:class="block3looks"} block to your code and update to show your chosen costume.

```blocks3
switch costume to [ v]  // update for your costume
```

To `hide`{:class="block3looks"} your sprite at the start of your project add a `hide`{:class="block3looks"} block to your code.

```blocks3
hide 
```

--- /collapse ---

--- collapse ---

---
title: Set the direction of your sprites
---

Your sprites might be facing the wrong way when you add them to your project. 

To change the direction of your sprite for the whole project, change the direction property and rotation style in the Sprite pane:

![direction property in the sprite pane](images/sprite-pane-direction.png)

To change the direction of your sprite for part of the project, add blocks to your code to change the `rotation style`{:class="block3motion"} and `direction`{:class="block3motion"}.

```blocks3
set rotation style [left-right v]
point in direction (-90) // turn to the left
```

--- /collapse ---

--- /task ---

--- task ---

Save your project

[[[generic-scratch3-saving]]]

--- /task ---

--- save ---
