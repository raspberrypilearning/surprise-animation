## Sorpresa

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Ahora necesitas agregar una sorpresa. ¿Qué podría pasar con el objeto? 
- ¿Se convertirá en otro objeto? 
- ¿Se convertirá en un personaje? 
- ¿Desaparecerá y revelará otro objeto? 

¡Tú decides!
</div>
<div>

![El proyecto 'Magia de gato' mostrando la sorpresa.](images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
¿Alguna vez has escrito una historia con un giro de la trama o una sorpresa? ¿Has visto un programa o leído un libro con un final impredecible? Puede utilizar los mismos métodos al crear una historia o animación digital. 
</p>

### ¿Cuándo ocurrirá la sorpresa?

--- task ---

Selecciona el objeto del **objeto**. Agrega un script para que la sorpresa comience cuando lo desees.

Deberás elegir un tiempo de espera que funcione para tu proyecto. Si tienes un personaje que pasa mucho tiempo siendo curioso, deberás elegir un mayor tiempo de espera.

[[[scratch3-time-delay]]]

--- /task ---

### ¡Ahora, crea la sorpresa!

--- task ---

El objeto podría `reproducir un sonido`{:class="block3sound"}, `cambiar de disfraz`{:class="block3looks"}, `cambiar de efectos gráficos`{:class="block3looks"} o `cambiar de tamaño`{:class="block3looks"}.

Podrías agregar un disfraz increíble al objeto, luego el objeto podría `cambiar de disfraz`{:class="block3looks"} para revelarlo. Por ejemplo, podrías hacer que una **Manzana** se convierta en un **Fantasma**.

[[[scratch3-add-costumes-to-a-sprite]]]

Puedes hacer que el objeto parezca convertirse en otro objeto diferente. Para hacer esto, debes `esconder`{:class="block3looks"} el objeto de **objeto** al mismo tiempo que `mostrar`{:class="block3looks"} otro objeto.

--- collapse ---
---
title: Esconde y muestra objetos
---

El objeto **Objeto**:
```blocks3
when [timer v] > (4) // set the delay
hide
```

Un objeto **sorpresa**:
```blocks3
when [timer v] > (4) // same delay
show
```

**Tip:** If you make a **surprise** sprite `show`{:class="block3looks"}, you will need to make it `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. ¿Ocurre la sorpresa en el momento adecuado? ¿La animación se reinicia correctamente?

--- /task ---

--- task ---

**Depurar:**

Si necesitas que un objeto esté delante o detrás de otro objeto, puedes utilizar capas:

[[[scratch3-positioning-with-layers]]]

Si la sorpresa ocurre en el momento equivocado, puedes solucionarlo:

--- collapse ---
---
title: Los scripts del cronómetro hacen ocurrir la sorpresa en el momento equivocado
---

Asegúrate de haber seleccionado la opción `cronómetro`{:class="block3events"} en el bloque `cuando volumen del sonido`{:class="block3events"}:

```blocks3
when [timer v] > [5]
```

Si haz seleccionado el `cronómetro`{:class="block3events"} correctamente, intenta ajustar el tiempo de espera del cronómetro.

--- /collapse ---

--- /task ---

--- save ---
