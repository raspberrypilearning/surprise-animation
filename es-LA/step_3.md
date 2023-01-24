## Show curiosity

Will the object do something to attract attention? How will the character react? You decide! Create the **second part** of your animation.

![A film strip with 3 frames. The second frame is highlighted. The frame shows a scene with character thinking 'hmmmm' while looking at a curious object.](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**Decomposition**</span> is breaking a project down into parts that are smaller and easier to understand. This means that you can build a project one part at a time until you have completed it. In this step you will focus only on the curiosity part of your animation.
</p>

### El objeto

--- task ---

**Elige:** Si deseas que el objeto haga algo, elige lo que hará.

![A desert background with a rock jiggling back and forth.](images/jiggle.gif)

Add blocks to the end of the 🎂🎾🎁 **interesting object's** `when green flag clicked`{:class="block3events"} setup script.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### El personaje

--- task ---

Get the 🐙👩‍🦼🦖 **main character** to show interest in the object. Add blocks to the end of the 🐙👩‍🦼🦖 **main character's** setup script.

If you need the 🐙👩‍🦼🦖 **main character** to wait until the 🎂🎾🎁 **interesting object** has done something, add a `wait`{:class="block3control"} block.

![A desert background with a rock jiggling back and forth.](images/bear.gif)

You could use `say`{:class="block3looks"} or `think`{:class="block3looks"} blocks, or even use the `Text to Speech`{:class="block3extensions"} extension to make the character talk out loud!

[[[scratch3-text-to-speech]]]

The character could emote, like in the [Space talk](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"} project.

[[[scratch3-change-costumes-to-show-mood]]]

The character could be brave and move closer to check out the object.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde para probar tu proyecto. The 🐙👩‍🦼🦖 **main character** should show curiosity about the object.

Click on the green flag again. If you changed the 🎂🎾🎁 **interesting object** or 🐙👩‍🦼🦖 **main character** sprite's position or looks, you will need to make sure that they are set back to their starting position or looks when you run the project again.

--- collapse ---
---
title: Establece la posición y apariencia iniciales del objeto
---

Elige los bloques que necesitas para establecer la posición y apariencia del objeto al principio.

```blocks3
when flag clicked // add blocks to set up the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**Consejo:** Todos los efectos gráficos se borran cuando haces clic en la bandera verde, por lo que no necesitas borrarlos, pero es posible que debas configurar los efectos que deseas que el objeto tenga.

--- /collapse ---

--- /task ---

--- task ---

**Debug:**

--- collapse ---
---
título: El sonido no funciona
---

Check that the volume on your computer or tablet is loud enough and that your speakers or headphones are connected and working properly.

--- /collapse ---

--- collapse ---
---
título: Mi animación no se restablece correctamente cuando hago clic en la bandera verde
---

Check that your project has `when green flag clicked`{:class="block3events"} scripts for the sprites that need them, and check that they reset the position, size, and looks for the sprites. For help with this, see the **Set the starting position and looks for a sprite** task above.

--- /collapse ---

--- /task ---

