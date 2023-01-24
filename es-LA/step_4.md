## Add a surprise!

Now, you need to add a surprise. What could happen to the object?
- Will it turn into another object?
- Will it turn into a character?
- Will it disappear and reveal another sprite?

You decide! Create the **third part** of your animation.

![A film strip with 3 frames. The third frame is highlighted. The frame shows a scene with character looking surprised at an object.](images/surprise.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Have you written a story with a plot twist or a surprise? Have you watched a show or read a book with an unpredictable ending? You can use the same methods when you create a digital story or animation. 
</p>

### ¿Cuándo ocurrirá la sorpresa?

--- task ---

Select the 🎂🎾🎁 **interesting object** sprite. Add a script to make the surprise start when you want it to.

Deberás elegir un tiempo de espera que funcione para tu proyecto. Si tienes un personaje que pasa mucho tiempo siendo curioso, deberás elegir un mayor tiempo de espera.

```blocks3
when flag clicked
wait (5) seconds // change the number to create your time delay
```

--- /task ---

### ¡Ahora, crea la sorpresa!

--- task ---

El objeto podría `reproducir un sonido`{:class="block3sound"}, `cambiar de disfraz`{:class="block3looks"}, `cambiar de efectos gráficos`{:class="block3looks"} o `cambiar de tamaño`{:class="block3looks"}.

You could add a surprising costume to the sprite, then the sprite could `switch costume`{:class="block3looks"} to reveal it.

![A desert background with a rock jiggling back and forth.](images/bat.gif)

[[[scratch3-add-costumes-to-a-sprite]]]

You could make the sprite seem to turn into a different sprite — to do this, `hide`{:class="block3looks"} the 🎂🎾🎁 **interesting object** sprite at the same time as you `show`{:class="block3looks"} another sprite.

--- collapse ---
---
title: Esconde y muestra objetos
---

The 🎂🎾🎁 **interesting object** sprite:
```blocks3
when flag clicked
show
wait (5) seconds
hide
```

The 🎷👻⚡**surprise object** sprite:
```blocks3
when flag clicked
hide
wait (5) seconds
show
```

**Consejo:** Si haces que un 🎷👻⚡**objeto sorpresa** `mostrar`{:class="block3looks"}, tendrás que hacerlo `ocultar`{:class="block3looks"} `cuando se haga clic en la bandera verde`{:clase="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. Does the surprise happen at the right time? Does the animation reset properly?

--- /task ---

--- task ---

**Debug:**

If you need a sprite to be in front of or behind another sprite, you can use layers:

[[[scratch3-positioning-with-layers]]]

If the surprise happens at the wrong time, you can fix that:

--- collapse ---
---
title: The surprise starts at the wrong time
---

You might need to change the amount of time in some or all of the `wait`{:class="block3control"} blocks, or add more `wait`{:class="block3control"} blocks, to get the timing just right.

--- /collapse ---

--- /task ---

