--- question ---
---
legend: Pregunta 2 de 3
---

En tu proyecto, planificaste tu animación con los bloques `cronómetro`{:class="block3events"} o `esperar`{:class="block3control"}.

En este proyecto de dinosaurios, quieres que el dinosaurio pequeño espere 6 segundos antes de salir del huevo y sorprender al dinosaurio grande.

![Un objeto dinosaurio y un objeto huevo en el Escenario.](images/quiz-q2.png)

¿Qué script del objeto **dinosaurio pequeño** haría que esto sucediera?

--- choices ---

- ( )
```blocks3
when [loudness v] > (6)
show
```

  --- feedback ---

 Estos son los bloques correctos para usar, pero debes seleccionar `cronómetro`{:class="block3events"} en lugar de `volumen del sonido`{: class = "block3events"} en el menú desplegable.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
show
```

  --- feedback ---

Este script necesita interacción del usuario para que se muestre el dinosaurio pequeño.

  --- /feedback ---

- ( )
```blocks3
when flag clicked
show
wait (6) seconds
```

  --- feedback ---

 Aquí, el dinosaurio pequeño sorprende al dinosaurio grande y luego espera 6 segundos.

  --- /feedback ---

- (x)
```blocks3
when [timer v] > (6)
show
```

  --- feedback ---

 Cuando el cronómetro ha esperado 6 segundos, ¡aparece el dinosaurio pequeño y sorprende al dinosaurio grande!

  --- /feedback ---

--- /choices ---

--- /question ---
