--- question ---
---
legend: Vraag 2 van 3
---

In je project heb je je animatie gepland met `klok`{:class="block3events"} of `wacht`{:class="block3control"} blokken.

In dit dinosaurusproject wil je dat de kleine dinosaurus 6 seconden wacht voordat hij uit het ei springt en de grote dinosaurus verrast.

![Een dinosaurus-sprite en een ei-sprite op het speelveld.](images/quiz-q2.png)

Welk script voor de **kleine dinosaurus** sprite zou dit mogelijk maken?

--- choices ---

- ( )
```blocks3
when [loudness v] > (6)
show
```

  --- feedback ---

 Dit zijn de juiste blokken om te gebruiken, maar je moet `klok`{:class="block3events"} selecteren in plaats van `volume`{:class="block3events"} in het vervolgkeuzemenu.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
show
```

  --- feedback ---

Dit script heeft gebruikersinteractie nodig om de kleine dinosaurus te laten verschijnen.

  --- /feedback ---

- ( )
```blocks3
when flag clicked
show
wait (6) seconds
```

  --- feedback ---

 Hier verrast de kleine dinosaurus de grote dinosaurus en wacht dan 6 seconden.

  --- /feedback ---

- (x)
```blocks3
when [timer v] > (6)
show
```

  --- feedback ---

 Als de klok 6 seconden heeft gewacht, verschijnt de kleine dinosaurus en verrast de grote dinosaurus!

  --- /feedback ---

--- /choices ---

--- /question ---
