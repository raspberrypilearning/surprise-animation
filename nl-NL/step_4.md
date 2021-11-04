## Verrassing

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Nu moet je een verrassing toevoegen. Wat kan er met het voorwerp gebeuren? 
- Zal het veranderen in een ander voorwerp? 
- Zal het een persoon worden? 
- Zal het verdwijnen en een andere sprite onthullen? 

Jij beslist!
</div>
<div>

![Het 'Kattenmagie'-project dat de verrassing laat zien.](images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Heb je een verhaal geschreven met een plotwending of een verrassing? Heb je een voorstelling gezien of een boek gelezen met een onvoorspelbaar einde? Je kunt dezelfde methoden gebruiken wanneer je een digitaal verhaal of animatie maakt. 
</p>

### Wanneer komt de verrassing?

--- task ---

Selecteer de **voorwerp** sprite. Voeg een script toe om de verrassing te laten beginnen wanneer jij dat wilt.

Je moet een vertraging kiezen die geschikt is voor jouw project. Als je een hoofdpersoon hebt die lang nieuwsgierig blijft, moet je een langere vertraging kiezen.

[[[scratch3-time-delay]]]

--- /task ---

### Creëer nu de verrassing!

--- task ---

Het voorwerp kan `een geluid starten`{:class="block3sound"}, `van uiterlijk veranderen`{:class="block3looks"}, `grafische effecten wijzigen`{:class="block3looks"}, of van `grootte veranderen`{:class="block3looks"}.

Je kunt een verrassend uiterlijk toevoegen aan de sprite, dan kan de sprite `van uiterlijk veranderen`{:class="block3looks"} om het te onthullen. Je kunt bijvoorbeeld de **Appel** veranderen in een **Spook**.

[[[scratch3-add-costumes-to-a-sprite]]]

Je zou de sprite kunnen laten lijken te veranderen in een andere sprite — om dit te doen, `verdwijnt`{:class="block3looks"} de **voorwerp** sprite op hetzelfde moment dat je andere sprite `verschijnt`{:class="block3looks"}.

--- collapse ---
---
title: Verdwijnen en verschijnen van sprites
---

De **voorwerp** sprite:
```blocks3
when [timer v] > (4) // stel de vertraging in
hide
```

Een **verrassing** sprite:
```blocks3
when [timer v] > (4) // dezelfde vertraging
show
```

**Tip:** Als je **verrassings**-sprite `verschijnt`{:class="block3looks"}, moet deze `verdwijnen`{:class="block3looks"} `wanneer op de groene vlag wordt geklikt`{:class="blok3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Test:** Klik op de groene vlag. Komt de verrassing op het juiste moment? Wordt de animatie correct opnieuw ingesteld?

--- /task ---

--- task ---

**Fouten oplossen:**

Als je een sprite voor of achter een andere sprite wilt hebben, kun je lagen gebruiken:

[[[scratch3-positioning-with-layers]]]

Als de verrassing op het verkeerde moment plaatsvindt, kun je dat oplossen:

--- collapse ---
---
title: Klokscripts starten de verrassing op het verkeerde moment
---

Zorg ervoor dat je de `klok`{:class="block3events"} optie hebt geselecteerd in het `wanneer volume`{:class="block3events"} blok:

```blocks3
when [timer v] > [5]
```

Als je de `klok`{:class="block3events"} correct hebt geselecteerd, probeer dan de tijd aan te passen die de klok wacht.

--- /collapse ---

--- /task ---

--- save ---
