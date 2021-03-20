## Surprise

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Now you need to add a surprise. What could happen to the object? 
- Will it turn into another object? 
- Will it turn into a character? 
- Will it disappear and reveal another sprite? 

You decide!
</div>
<div>
![Cat magic project showing the surprise](images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Have you written a story with a plot twist or a surprise? Maybe you have watched a show or read a book with an unpredictable ending? You can use the same methods when creating a digital story or animation. 
</p>

When will your surprise happen?

--- task ---
Select the **object** sprite and add a script to start the surprise. 

[[[scratch3-time-delay]]]

--- /task ---

Now, create your surprise!

--- task ---

The object could `play a sound`{:class="block3sound"}, `switch costume`{:class="block3looks"}, `change graphic effects`{:class="block3looks"}, `change size`{:class="block3looks"}.

You could add a surprising costume to a sprite and then `switch costume`{:class="block3looks"}, such as the Apple turning into a Ghost:

[[[scratch3-add-costumes-to-a-sprite]]]

You could make a sprite appear to turn into a different sprite by hiding one sprite at the same time as you show another.

--- collapse ---

---
title: Hide and show sprites
---

**Object sprite**
```blocks3
when [timer v] > (4) // set the delay
hide
```

**Surprise sprite**
```blocks3
when [timer v] > (4) // same delay
show
```

**Tip:** If you make a different object `show`{:class="block3looks"}, then you will need to make it `hide`{:class="block3looks"} `when flag clicked`{:class="block3events"}

--- /collapse ---

--- /task ---

--- task ---

**Test:** Click on the green flag and try your project out, does the surprise happen at the right time? Does the animation reset properly when you click the green flag?

--- /task ---

--- task ---

**Debug:**

If you need a sprite to be in front or behind another sprite, you can use `layers`{:class="block3looks"}.

[[[scratch3-positioning-with-layers]]]

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

--- /task ---

--- save ---
