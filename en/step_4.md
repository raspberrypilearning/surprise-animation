## Surprise

Now you need to add a surprise. What could happen to the object? 
- Will it turn into another object? 
- Will it turn into a character? 
- Will it disappear and reveal another sprite? 

You decide!

--- task ---

Set when the surprise will start. 

[[[scratch3-time-delay]]]


--- /task ---


--- task ---

The object could `play a sound`{:class="block3sounds"}, `switch costume`{:class="block3looks"}, `change graphic effects`{:class="block3looks"}, `change size`{:class="block3looks"}. It could hide and another object could appear in its place. It could do a few of these things. 

--- collapse ---

---
title: Copy costumes from one sprite to another
---

Click on the Costumes tab and then 'Choose a costume' to add any costume to the sprite. 

![Choose a costume menu highlighted](images/choose-a-costume.png)

You will need to position and resize the added costumes in the Paint editor to match your other costumes.


**Tip:** If you position a sprite on the Stage and then switch costume the sprite might appear to 'jump' or change size. You will need to position and resize the costumes in the **Paint editor** so that they all appear in the right position on the Stage. 

--- /collapse ---

You could make a sprite appear to turn into a different sprite by hiding one sprite and showing the other at the same time.

You'll need to add another sprite if you choose this option.

<mark>scratch3-show-hide-sprites</mark>

**Tip:** If you make a different object `show`{:class="block3looks"}, then you will need to make it `hide`{:class="block3looks"} `when flag clicked`{:class="block3events"}

--- /collapse ---

You could create a new costume by copying parts from one sprites's costume to another.


[[[scratch3-copy-parts-between-sprite-costumes]]]


--- /task ---

--- task ---

**Test:** Click on the green flag and try your project out, does the surprise happen at the right time? 

--- /task ---

--- task ---

**Debug:**

If you need a sprite to be in front or behind another sprites, you can use `layers`{:class="block3looks"}.

<mark>generic-scratch3-positioning-with-layers</mark>


--- collapse ---

---
title: Timer scripts trigger at the wrong time
---

Make sure you have selected the `timer`{:class="block3sensing"} option in the `when [loudness v]`{:class="block3sensing"} block:

```blocks3
when [timer v] > [5]
```

If you have the `timer`{:class="block3sensing"} selected correctly then you can try adjusting the amount of time that the timer waits.

--- /collapse ---

--- collapse ---

---
title: Sprites don't go back to their starting settings
---

Make sure you have added code `when flag clicked`{:class="block3events"} to reset any changes to `Looks`{:class="block3looks"} or `Motion`{:class="block3motion"} blocks. For example:

```blocks3
when flag clicked 
go to x: () y:() // comment
set size to () %
switch costume to [ v]
hide
point in direction ()
```

--- /collapse ---

--- /task ---

--- save ---
