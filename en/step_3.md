## Curiosity

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1">  

Now your character can show curiosity about the object:
- Will your object do something to attract attention? 
- Will your character move towards the object to check it out? 
- Will it use speech or costume changes? 

You decide!

<div>
![BOO! project showing curiosity](images/boo.png)
</div>
</div>

### The object

Why is your character curious about the object? It could just be a strange object for the environment, or something that naturally has a surprise. Or you may want it to attract attention. 

--- task ---

You can get your object to do something to make the character curious about it. 

--- collapse ---

---
title: Jiggle a sprite to attract attention
---

```blocks3
repeat [8]
turn left [15] degrees
wait [0.1] secs
turn right [15] degrees
wait [0.1] secs
turn right [15] degrees
wait [0.1] secs
turn left [15] degrees
wait [0.1] secs
end
```
--- /collapse ---

You could `change`{:class="block3looks"} or `set`{:class="block3looks"} the `colour effect`{:class="block3looks"} to attract attention to the object.

[[[scratch3-graphic-effects]]]

--- /task ---

### The character

Get your main character to express interest in the object.

--- task ---

You can use `say`{:class="block3looks"} or `think`{:class="block3looks"} blocks, or animate your character with costumes or movement.

You can also use the text to speech extension to make a sprite talk out loud!

[[[scratch3-text-to-speech]]]

You can also make your sprite emote like in [Space talk](https://projects.raspberrypi.org/en/projects/space-talk). 

[[[scratch3-change-costumes-to-show-mood]]]

You can make your character move to check out the object:

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
set size [100] % // starting size
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
**Test:** Click the green flag again and make sure your character goes back to it's normal `position`{:class="block3motion"} and `looks`{:class="block3looks"} `when green flag clicked`{:class="block3events"}, before it shows curiosity at the object.

--- /task ---

--- task ---
**Debug:**

--- collapse ---

---
title: The sound is not working
---

Check that the computer volume is loud enough and that your speakers or headphones are connected and working properly. 

--- /collapse ---

--- /task ---


--- save ---