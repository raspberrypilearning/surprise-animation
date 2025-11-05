## Lägg till en överraskning!

Nu behöver du lägga till en överraskning. Vad skulle kunna hända med föremålet?
- Kommer det att förvandlas till ett annat föremål?
- Kommer det att bli en karaktär?
- Kommer den att försvinna och avslöja en annan sprajt?

Du väljer! Skapa den **tredje delen** av din animering.

![En filmremsa med 3 bilder. Den tredje bilden är markerad. Bilden visar en scen med en karaktär som tittar förvånat på ett föremål.](images/surprise.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Har du skrivit en berättelse med en plottwist eller överraskning? Har du sett en serie eller läst en bok med ett oförutsägbart slut? Du kan använda samma metoder när du skapar en digital berättelse eller animering. 
</p>

### När kommer överraskningen att hända?

--- task ---

Välj 🎂🎾🎁 **intressant objekts**sprajten. Lägg till kod som får överraskningen att starta när du vill det.

Du bör välja en tidsfördröjning som fungerar för ditt projekt. Om du har en karaktär som är nyfiken länge bör du välja en längre fördröjning.

```blocks3
when flag clicked
wait (5) seconds // change the number to create your time delay
```

--- /task ---

### Skapa nu överraskningen!

--- task ---

Objektet kan `spela ett ljud`{:class="block3sound"}, `byta klädsel`{:class="block3looks"}, `ändra bildeffekter`{:class="block3looks"} eller `ändra storlek`{:class="block3looks"}.

Du kan skapa en överraskande klädsel för sprajten som den sedan kan `ändra klädsel till`{:class="block3looks"} för att visa.

![En ökenbakgrund med en sten som vickar fram och tillbaka.](images/bat.gif)

[[[scratch3-add-costumes-to-a-sprite]]]

Du kan få sprajten att verka förvandlas till en annan sprajt — för att göra detta, `dölj`{:class="block3looks"} den🎂🎾🎁 **intressanta objekt** sprajten samtidigt som du `visar`{:class= "block3looks"} en annan sprajt.

--- collapse ---
---
title: Hide and show sprites
---

Den 🎂🎾🎁 **intressanta objekt**sprajten:
```blocks3
when flag clicked
show
wait (5) seconds
hide
```

🎷👻⚡**överraskningsobjekt**sprajten:
```blocks3
when flag clicked
hide
wait (5) seconds
show
```

**Tips:** Om du får 🎷👻⚡**överraskningsobjektet**att `visas`{:class="block3looks"}, måste du `dölja`{:class="block3looks"} den `när den gröna flaggan klickas på`{:class="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Test:** Klicka på den gröna flaggan. Händer överraskningen vid rätt tidpunkt? Återställs animeringen ordentligt?

--- /task ---

--- task ---

**Debug (Felsökning):**

Om du vill att en sprajt ska vara framför eller bakom en annan sprajt kan du använda lager:

[[[scratch3-positioning-with-layers]]]

Om överraskningen sker vid fel tidpunkt kan du fixa det:

--- collapse ---
---
title: The surprise starts at the wrong time
---

Du kan behöva ändra tiden i några eller alla av de `vänta`{:class="block3control"}blocken eller lägga till fler `vänta`{:class="block3control"}block, för att få rätt timing.

--- /collapse ---

--- /task ---

