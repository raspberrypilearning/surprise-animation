## Curiosity 

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Why is your character curious about the object?

- Will your object do something to attract attention?
- Will your character move towards the object to check it out?
- Will it use speech or costume changes?

You decide!
</div>
<div>
![The 'BOO!' project showing curiosity.](images/boo.png)
</div>
</div>

### The object

--- task ---

If your object needs to do something to make the character curious about it, add blocks to the end of the **object's** `when green flag clicked`{:class="block3events"} setup script.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### The character

--- task ---

Get your main character to express interest in the object. Add blocks to the end of the **character's** setup script. 

If you need to wait until the object has done something, add a `wait`{:class="block3control"} block.

You could choose to use `say`{:class="block3looks"} or `think`{:class="block3looks"} blocks and even use the `Text to Speech`{:class="block3extensions"} extension to make a sprite talk out loud!

[[[scratch3-text-to-speech]]]

Your character could emote, like in the [Space talk](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"} project. 

[[[scratch3-change-costumes-to-show-mood]]]

Your character could be brave and move closer to check out the object.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---
**Test:** Click on the green flag to try your project. Your sprite should show curiosity about the object. 

Click on the green flag again. If you changed your sprite's looks or position, then you will need to make sure that they are set back to normal.

--- collapse ---

---
title: Setting the starting position and looks for a sprite
---

Choose the blocks that you need to get your sprite to be in the right position and have the right looks at the start.

```blocks3
when flag clicked // add blocks to set the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**Tip:** All graphic effects are cleared when you click on the green flag, so you don't need to clear them, but you might need to set the values that you want. 

--- /collapse ---

--- /task ---

--- task ---
**Debug:**

--- collapse ---

---
title: The sound is not working
---

Check that the computer volume is loud enough and that your speakers or headphones are connected and working properly. 

--- /collapse ---

--- collapse ---

---
title: My animation does not reset properly when I click on the green flag
---

Check that you have `when green flag clicked`{:class="block3events"} scripts for the sprites that need it, and check that they reset the position, size, and looks. See **Setting the starting position and looks for a sprite** above for more help.

--- /collapse ---

--- /task ---

--- save ---
