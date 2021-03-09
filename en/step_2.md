## Setup

Have you got an idea about your story? In this step, add a backdrop, main character and interesting object. 

--- task ---

Open a [new Scratch project](https://scratch.mit.edu/projects/editor){:target=”_blank”} to look at the range of sprites and backdrops. Spend some time thinking about your main character, interesting object and backdrop.

--- /task ---

--- task ---

Choose a sprite for your main character and another sprite to be the interesting object.

[[[generic-scratch3-sprite-from-library]]]

--- collapse ---

---
title: Paint your own character or object
---

You can create a character from shapes using the rectangle and oval tools. 

Don't add the eyes, they need to be separate sprites.

![Pig costume created using the paint editor](images/pig-costume.png)

--- /collapse ---

--- /task ---

Where do you want your story to take place?

--- task ---

Your animation can take place anywhere you like. **Choose** a backdrop to set the scene. 

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

Where do you want your sprites to be at the beginning of the story? How big will they be? How should they look?

--- task ---

Getting your sprites ready for the start of the story is an important task. You will need to add code `when flag clicked`{:class="block3events"} that reset your sprites at the beginning of your animation. 

Remember to set up your main character and your interesting object.

--- collapse ---

---
title: Position your sprites
---

Move your main character to a good starting position on the Stage. 

Add a `go to x y`{:class="block3motion"} block to your code.

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
set size to 100% // <100% smaller >100% bigger
```

--- /collapse ---

--- collapse ---

---
title: Set the costume
---



```blocks3
switch costume to [ v]  // update for your costume
```

--- /collapse ---

--- /task ---

--- save ---