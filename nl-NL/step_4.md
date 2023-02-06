## Voeg een verrassing toe!

Nu moet je een verrassing toevoegen. Wat kan er met het voorwerp gebeuren?
- Zal het veranderen in een ander voorwerp?
- Zal het een personage worden?
- Zal het verdwijnen en een andere sprite onthullen?

Jij beslist! Maak het **derde deel** van je animatie.

![Een filmstrip met 3 frames. Het derde frame is gemarkeerd. Het beeld toont een scène met een personage dat verbaasd naar een object kijkt.](images/surprise.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Heb je een verhaal geschreven met een plotwending of een verrassing? Heb je een voorstelling gezien of een boek gelezen met een onvoorspelbaar einde? Je kunt dezelfde methoden gebruiken wanneer je een digitaal verhaal of animatie maakt. 
</p>

### Wanneer komt de verrassing?

--- task ---

Selecteer de 🎂🎾🎁 **interessant voorwerp** sprite. Voeg een script toe om de verrassing te laten beginnen wanneer jij dat wilt.

Je moet een vertraging kiezen die geschikt is voor jouw project. Als je een hoofdpersoon hebt die lang nieuwsgierig blijft, moet je een langere vertraging kiezen.

```blocks3
when flag clicked
wait (5) seconds // verander de vertraging
```

--- /task ---

### Creëer nu de verrassing!

--- task ---

Het voorwerp kan `een geluid starten`{:class="block3sound"}, `van uiterlijk veranderen`{:class="block3looks"}, `grafische effecten wijzigen`{:class="block3looks"}, of van `grootte veranderen`{:class="block3looks"}.

Je zou een verrassend uiterlijk aan de sprite kunnen toevoegen, dan zou de sprite van uiterlijk `{`class="block3looks"} kunnen wisselen om het te onthullen.

![Een woestijnachtergrond met een rots die heen en weer schudt.](images/bat.gif)

[[[scratch3-add-costumes-to-a-sprite]]]

Je zou de sprite kunnen laten lijken te veranderen in een andere sprite — om dit te doen, `verdwijn`{:class="block3looks"}t de 🎂🎾🎁 **interessante object** sprite terwijl tegelijk een andere sprite `verschijn`{:class="block3looks"}t.

--- collapse ---
---
title: Verdwijnen en verschijnen van sprites
---

De 🎂🎾🎁 **interessante object** sprite:
```blocks3
when flag clicked
show
wait (5) seconds
hide
```

De 🎷👻⚡**verrassingsobject** sprite:
```blocks3
when flag clicked
hide
wait (5) seconds
show
```

**Tip:** Als je een 🎷👻⚡**verrassingsobject** sprite laat `verschijn`{:class="block3looks"} en, moet je deze laten `verdwijn`{:class="block3looks"} en `wanneer op de groene vlag wordt geklikt`{:class="block3events"}.

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
title: De verrassing begint op het verkeerde moment
---

Mogelijk moet je de hoeveelheid tijd in sommige of alle `wacht`{:class="block3control"}-blokken wijzigen, of meer `wacht`{:class="block3control"}-blokken toevoegen om de timing precies goed te krijgen.

--- /collapse ---

--- /task ---

