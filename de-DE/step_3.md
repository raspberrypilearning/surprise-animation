## Zeige Neugier

Wird das Objekt etwas tun, um Aufmerksamkeit zu erregen? Wie wird der Charakter reagieren? Es ist deine Entscheidung! Erstelle den **zweiten Teil** deiner Animation.

![Ein Filmstreifen mit 3 Bildern. Der zweite Rahmen (frame) ist hervorgehoben. Der Rahmen zeigt eine Szene, in der der Charakter „hmmmm“ denkt, während er ein merkwürdiges Objekt betrachtet.](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**Zerlegung**</span> ist die Aufteilung eines Projekts in kleinere und leichter verständliche Teile. Dies bedeutet, dass du ein Projekt Stück für Stück aufbauen kannst, bis du es abgeschlossen hast. In diesem Schritt konzentrierst du dich nur auf den Neugier-Teil deiner Animation.
</p>

### Das Objekt

--- task ---

**Wähle:** Wenn das 🎂🎾🎁 **interessante Objekt** etwas tun soll, um Aufmerksamkeit zu erregen, wähle aus, was das Objekt tun soll.

![Ein Wüstenhintergrund mit einem hin und her wackelnden Felsen.](images/jiggle.gif)

Füge Blöcke in deinem🎂🎾🎁 **interessanten Objekt** am Ende des `Wenn grüne Flagge angeklickt wird`{:class="block3events"}-Skripts hinzu.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### Der Charakter

--- task ---

Bringe die 🐙👩‍🦼🦖 **Hauptfigur** dazu, Interesse an dem Objekt zu zeigen. Füge Blöcke am Ende des Setup-Skripts der 🐙👩‍🦼🦖 **Hauptfigur** hinzu.

Wenn die 🐙👩‍🦼🦖 **Hauptfigur** warten soll, bis das 🎂🎾🎁 **interessante Objekt** etwas getan hat, füge einen `warte`{:class="block3control"}-Block hinzu.

![Ein Wüstenhintergrund mit einem hin und her wackelnden Felsen.](images/bear.gif)

Du könntest `sage`{:class="block3looks"} oder `denke`{:class="block3looks"}-Blöcke verwenden, oder sogar die Erweiterung `Text zu Sprache`{:class="block3extensions"}, um die Figur laut sprechen zu lassen!

[[[scratch3-text-to-speech]]]

Der Charakter könnte Emotionen zeigen, wie im Projekt [Weltraumgespräch](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

Der Charakter könnte mutig sein und näher herangehen, um das Objekt zu erkunden.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Test:** Klicke auf die grüne Flagge, um dein Projekt zu testen. Die 🐙👩‍🦼🦖 **Hauptfigur** sollte Neugierde hinsichtlich des Objekts zeigen.

Klicke erneut auf die grüne Flagge. If you changed the 🎂🎾🎁 **interesting object** or 🐙👩‍🦼🦖 **main character** sprite's position or looks, you will need to make sure that they are set back to their starting position or looks when you run the project again.

--- collapse ---
---
title: Lege die Startposition und das Aussehen einer Figur fest
---

Wähle die Blöcke aus, um die Position und das Aussehen beim Start festzulegen.

```blocks3
when flag clicked // add blocks to set up the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**Tip:** All graphic effects are cleared when you click on the green flag, so you don't need to clear them, but you might need to set the effects that you want the sprite to have.

--- /collapse ---

--- /task ---

--- task ---

**Fehlersuche:**

--- collapse ---
---
title: Der Ton funktioniert nicht
---

Überprüfe, ob die Lautstärke deines Computers oder Tablets hoch genug ist und ob deine Lautsprecher oder Kopfhörer angeschlossen sind und ordnungsgemäß funktionieren.

--- /collapse ---

--- collapse ---
---
title: Meine Animation wird nicht richtig zurückgesetzt, wenn ich auf die grüne Flagge klicke
---

Überprüfe, ob dein Projekt `wenn grüne Flagge angeklickt wird`{:class="block3events"}-Skripte für die Figuren enthält, die dies benötigen und dort die Position, Größe und das Aussehen der Figuren zurückgesetzt werden. Hilfe hierzu findest du in der obigen Aufgabe **Lege die Startposition und das Aussehen einer Figur fest **.

--- /collapse ---

--- /task ---

