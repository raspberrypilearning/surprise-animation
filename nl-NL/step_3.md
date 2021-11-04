## Nieuwsgierigheid

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Zal het voorwerp iets doen om de aandacht te trekken? Hoe zal de hoofdpersoon reageren?

Jij beslist!
</div>
<div>

![Het 'BOE!' project waarbij de hoofdpersoon nieuwsgierig is.](images/boo.png)

</div>
</div>

### Het voorwerp

--- task ---

**Kies:** Als je wilt dat het voorwerp iets doet, kies dan wat het voorwerp zal doen.

Blokken toe te voegen aan het einde van het **voorwerp** zijn `als op de groene vlag wordt geklikt`{:class="block3events"} instel-script.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### De hoofdpersoon

--- task ---

Laat de hoofdpersoon interesse tonen voor het voorwerp. Voeg blokken toe aan het einde van het instel-script van de **hoofdpersoon**.

Als je wilt dat de hoofdpersoon wacht totdat het voorwerp iets heeft gedaan, voeg je een `wacht`{:class="block3control"}-blok toe.

Je zou `zeg`{:class="block3looks"} of `denk`{:class="block3looks"} blokken kunnen gebruiken, of zelfs de `Tekst naar spraak`{:class="block3extensions"} extensie gebruiken om de hoofdpersoon hardop te laten praten!

[[[scratch3-text-to-speech]]]

De hoofdpersoon kan emoties tonen, zoals in het [Ruimtespraak](https://projects.raspberrypi.org/nl-NL/projects/space-talk){:target="_blank"}-project.

[[[scratch3-change-costumes-to-show-mood]]]

De hoofdpersoon kan dapper zijn en dichterbij komen om het voorwerp te bekijken.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Test:** Klik op de groene vlag om je project te testen. De hoofdpersoon moet nieuwsgierig zijn naar het voorwerp.

Klik nogmaals op de groene vlag. Als je de **voorwerp** of **hoofdpersoon** sprite hebt gewijzigd, moet je ervoor zorgen dat ze terug worden gezet naar hun startpositie of uiterlijk wanneer je het project opnieuw uitvoert.

--- collapse ---
---
title: Stel de startpositie en uiterlijk in voor een sprite
---

Kies de blokken die je nodig hebt om de positie en uiterlijk aan het begin in te stellen voor een sprite.

```blocks3
when flag clicked // voeg blokken toe om de start in te stellen 
switch costume to [costume1 v]
set size to (100) % // startgrootte
go to x: (-200) y: (50) // startpositie
point in direction [90]
set [brightness v] effect to [80]
show
```

**Tip:** Alle grafische effecten worden gewist wanneer je op de groene vlag klikt, dus je hoeft ze niet te wissen, maar je moet mogelijk de effecten instellen die je wilt dat de sprite heeft.

--- /collapse ---

--- /task ---

--- task ---

**Fouten oplossen:**

--- collapse ---
---
title: Het geluid werkt niet
---

Controleer of het volume op jouw computer of tablet luid genoeg is en of jouw luidsprekers of hoofdtelefoons zijn aangesloten en goed werken.

--- /collapse ---

--- collapse ---
---
title: Mijn animatie wordt niet goed opnieuw ingesteld als ik op de groene vlag klik
---

Controleer of je project `wanneer op de groene vlag wordt geklikt`{:class="block3events"}-scripts heeft voor de sprites die ze nodig hebben, en controleer of ze de positie, grootte en uiterlijk van de sprites opnieuw instellen. Voor hulp hierbij, zie de **Stel de startpositie en uiterlijk in voor een sprite** taak hierboven.

--- /collapse ---

--- /task ---

--- save ---
