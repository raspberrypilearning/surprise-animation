## Configuración

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
¿Tienes alguna idea sobre tu animación? 
  
En este paso, agregarás un fondo, un personaje principal y un objeto interesante. 
</div>
<div>  
![El proyecto '¡Sorpresa! Dinosaurio' ya configurado.](images/dinosaur-surprise.png)
</div>
</div>

--- task ---

Abre el proyecto de inicio [¡Sorpresa! animación](https://scratch.mit.edu/projects/582222532/editor){:target="_blank"} y mira la gama de objetos y fondos que puedes usar. Dedica algún tiempo a pensar en tu personaje principal, objeto interesante y fondo.

--- /task ---

--- task ---

**Choose:** Choose a sprite to be the main character and another sprite to be the interesting object.

![El ícono 'Elegir un objeto'.](images/add-sprite.png)

--- /task ---

¿Dónde quieres que se lleve a cabo tu animación?

--- task ---

**Elige:** Elige un fondo para establecer la escena.

![El ícono 'Elige un fondo'.](images/add-backdrop.png)

--- /task ---

¿Dónde quieres que empiecen tus objetos? ¿Qué tan grandes quieres que sean? ¿Cómo quieres que luzcan?

--- task ---

Agrega un bloque`al presionar bandera verde ⚑`{:class="block3events"}, luego, debajo, agrega bloques para configurar tus objetos al comienzo de tu animación.

Recuerda configurar tanto tu **personaje principal** como tu **objeto interesante**.

--- collapse ---
---
title: Posiciona tus objetos
---

Para cambiar la posición del objeto del **personaje principal** para todo el proyecto, muévelo a la posición que quieras en el escenario.

Para cambiar la posición del objeto del **personaje principal** para parte del proyecto, mueve el personaje principal a la posición de tu elección en el escenario, luego agrega un bloque `ir a x: y:`{:class="block3motion"} a tu código:

```blocks3
go to x: (0) y: (0) // add the sprite's position
```

Repite esta tarea para el **objeto interesante**.

--- /collapse ---

--- collapse ---
---
title: Cambia el tamaño de tus objetos
---

Para cambiar el tamaño de un objeto para todo el proyecto, cambia el número en la propiedad **Tamaño** en el Panel de objetos:

![](images/sprite-pane-size.png)

Para cambiar el tamaño de un objeto para parte del proyecto, agrega código a `fijar tamaño a`{:class="block3looks"} el tamaño de su elección. This option is good if you want your sprite to change size in the project.

```blocks3
set size to [100] % // <100 is smaller, >100 is bigger
```

--- /collapse ---

--- collapse ---
---
title: Configura los disfraces de tus objetos
---

Para cambiar el disfraz de un objeto para todo el proyecto, haz clic en la pestaña **Disfraces** y selecciona uno de los disfraces disponibles:

![La pestaña Disfraces, con los disfraces disponibles para un objeto.](images/nano-costumes.png)

Para cambiar el disfraz de un objeto para parte del proyecto, agrega un bloque `cambiar disfraz a`{:class="block3looks"} a tu código y actualízalo para que se muestre el disfraz de tu elección:

```blocks3
switch costume to [ v]  // update this for your chosen costume
```

Para ocultar un objeto al inicio del proyecto, agrega un bloque `esconder`{:class="block3looks"} a tu código:

```blocks3
hide 
```

--- /collapse ---

--- collapse ---
---
title: Configura la dirección de tus objetos
---

Es posible que tus objetos estén orientados de manera incorrecta cuando los agregues a su proyecto.

Para cambiar la dirección de un objeto para todo el proyecto, cambia la **Dirección** y el ** Estilo de rotación** en el Panel de objetos:

![El menú Dirección y estilo de rotación en el Panel de objetos.](images/sprite-pane-direction.png)

Para cambiar la dirección de un objeto para parte del proyecto, agrega bloques a tu código para cambiar el `estilo de rotación`{:class="block3motion"} y la `dirección`{: class = "block3motion"}:

```blocks3
set rotation style [left-right v]
point in direction (-90) // turn to the left
```

--- /collapse ---

--- /task ---

--- task ---

Guarda tu proyecto.

[[[generic-scratch3-saving]]]

--- /task ---

--- save ---
