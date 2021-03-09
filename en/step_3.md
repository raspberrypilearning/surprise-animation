## Curiosity

Now your character can show curiosity about the object:
- Will your object do something to attract attention? 
- Will your character move towards the object to check it out? 
- Will it use speech or costume changes? 

You decide!

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

--- collapse ---

---
title: Graphic effects in action
---

**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

```blocks3 
change [color v] effect by [10]

set [whirl v] effect to [100]
```

+`color`{:class="block3looks"}: From 0 to 199 (bigger numbers will wrap around, so 200 is the same as 0)
+`fisheye`{:class="block3looks"}: 0 is no effect, bigger numbers give a bigger ‘bulge’ effect
+`whirl`{:class="block3looks"}: 0 is no effect, big number gives a big whirl to the left, big negative number gives a big whirl to the right
+`pixelate`{:class="block3looks"}: 0 is no effect, bigger numbers create more pixels
+`mosaic`{:class="block3looks"}: 0 is no effect, bigger numbers create more copies
+`brightness`{:class="block3looks"}: 0 is no effect, bigger numbers up to 100 make the sprite lighter, and negative numbers down to -100 make the sprite darker
+`ghost`{:class="block3looks"}: 0 is no effect, bigger numbers up to 100 make the sprite more transparent

**Tip:** A colour effect of 225 is the same as a colour effect of 25 so you can keep changing the colour. For other effects nothing will happen after you reach the maximum number for the effect. You can click on `clear graphic effects`{:class="block3looks"} in the `Looks`{:class="block3looks"} Blocks menu or click on the green flag to start again.

**Tip:** Changing the `colour effect`{:class="block3looks"} inside a `forever`{:class="block3control"} loop with a `wait`{:class="block3control"} creates a cool effect.

--- /collapse ---

--- /task ---

### The character

Get your main character to express interest in the object.

--- task ---

You can use `say`{:class="block3looks"} or `think`{:class="block3looks"} blocks, or animate your character with costumes or movement.

You can also use the text to speech extension to make a sprite talk out loud!

--- collapse ---

---
title: Using the text to speech extension
---

Click Add Extension:

![Add extension button](images/add-extension.png)

Choose Text to Speech

![Text to Speech extension highlighted](images/text-to-speech.png)

You will get new a new Text to Speech Blocks menu:

![Text to Speech blocks menu](images/text-to-speech-extension.png)

You can use these blocks to make your sprites talk out loud.

Make a sprite talk:

```blocks3
set voice to (alto v) :: tts // choose a voice
set language to (English v) :: tts 
speak [Kitty, have you been messing with my potions again?] :: tts
```

You can even use kitten speak!

```blocks3
set voice to (kitten v) :: tts
speak [Cat gotta haz milk.] :: tts
```

--- /collapse ---

You can also emote your sprite like in Space Talk(link). 

--- collapse ---

---
title: Emote your sprite to show their mood
---

<div>
**Abby says hmm**: [See inside](https://scratch.mit.edu/projects/498767227/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed//498767227/?autostart=false" frameborder="0"></iframe>
</div>

You can change costume before and after a `say for`{:class="block3looks"}, `think for`{:class="block3looks"}, `play sounds`{:class="block3sounds"}, or `wait`{:class="block3events"} block to make you character show their feelings.

```blocks3
switch costume to [abby-a v] // normal costume
wait [1] secs
switch costume to [abby-b v] // show feelings
think [Hmm...] for [2] secs
switch costume to [abby-a v] // back to normal
```

**Tip:** Make sure you use a block that takes time, not a `start sound`{:class="block3sound"} or `say`{:class="block3looks"} or `think`{:class="block3looks"} block, otherwise you won't see the costume change.

--- /collapse ---

You can make your character move to check out the object:

--- collapse ---

---
title: Animate character movement with costumes
---

```blocks3
repeat [20] // how many times to move
switch costume to [hedgehog-a v]
move [3] steps // how much to move in one go
wait [0.1] secs // try 0.2 0.5 0.01
switch costume to [hedgehog-b v]
move [3] steps
wait [0.1] secs
end
```

**Tip:** Increase the number of steps in each `move`{:class="block3motion"} to go faster. Change the number in the `repeat`{:class="block3control"} block to adjust the distance.

**Tip:** To move backwards you can use negative numbers `move [-3]`{:class="block3motion"}. Or, you can use a `point in direction [-90]`{:class="block3motion"} to change the sprite's direction before moving, `-90` points to the left. 

--- /collapse ---

--- /task ---

--- task ---
**Test:** Click the green flag to try your project. Your sprite should show curiosity about the object.

--- /task ---

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
```

**Tip:** All graphic effects are cleared when you click the green flag so you don't need to clear them but you might need to set the values you want.

--- /collapse ---

--- task ---

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