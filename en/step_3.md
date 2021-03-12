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
![BOO! project showing curiosity](images/boo.png)
</div>
</div>

### The object

--- task ---

You can get your object to do something to make the character curious about it. 

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### The character

Get your main character to express interest in the object.

--- task ---

You can use `say`{:class="block3looks"} or `think`{:class="block3looks"} blocks.

You can also use the text to speech extension to make a sprite talk out loud!

[[[scratch3-text-to-speech]]]

Or, make your sprite emote like in [Space talk](https://projects.raspberrypi.org/en/projects/space-talk). 

[[[scratch3-change-costumes-to-show-mood]]]

Or, make your character move to check out the object:

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---
**Test:** Click the green flag to try your project. Your sprite should show curiosity about the object.

--- /task ---

--- task ---

If you changed your sprite's looks or position then you will need to make sure they are set back to normal when you click the green flag.

--- collapse ---

---
title: Setting start position and looks for a sprite
---

Choose the blocks you need to get your sprite into the right position and with the right looks at the start.

```blocks3
when flag clicked // Add blocks to set the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
say () // say nothing
show
```

**Tip:** All graphic effects are cleared when you click the green flag so you don't need to clear them but you might need to set the values you want.

--- /collapse ---

--- /task ---

--- task ---
**Test:** Click the green flag again and make sure your character goes back to its normal `position`{:class="block3motion"} and `looks`{:class="block3looks"} `when green flag clicked`{:class="block3events"}, before it shows curiosity at the object.

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
title: My animation doesn't reset properly when I click the green flag
---

Check that you have `when green flag clicked`{:class="block3events"} scripts for the sprites that need it and check that they reset the position, size and looks. See **Setting start position and looks for a sprite** above for more help.

--- /collapse ---

--- /task ---

--- save ---
