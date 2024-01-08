## Mostra curiosità

L'oggetto farà qualcosa per attirare l'attenzione? Come reagirà il personaggio? Lo decidi tu! Crea la **seconda parte** della tua animazione.

![Una striscia di pellicola con 3 fotogrammi. Il secondo fotogramma è evidenziato. Il fotogramma mostra una scena in cui il personaggio pensa "hmm" mentre guarda un oggetto curioso.](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**Scomposizione**</span> significa suddividere un progetto in parti più piccole e più facili da capire. Ciò significa che puoi costruire un progetto una parte alla volta finché non lo hai completato. In questo passaggio ti concentrerai solo sulla fase "curiosità" della tua animazione.
</p>

### L'oggetto

--- task ---

**Scegli:** Se vuoi che l' 🎂🎾🎁 **oggetto interessante** faccia qualcosa per attirare l'attenzione, scegli cosa farà.

![Uno sfondo desertico con una roccia che si muove avanti e indietro.](images/jiggle.gif)

Aggiungi blocchi alla fine dello script di setup dell' 🎂🎾🎁 **oggetto interessante**, dopo il blocco `quando si clicca sulla bandierina verde`{:class="block3events"}.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### Il personaggio

--- task ---

Fai in modo che il 🐙👩‍🦼🦖 **personaggio principale** mostri interesse per l'oggetto. Aggiungi blocchi alla fine dello script di setup del 🐙👩‍🦼🦖 **personaggio principale**.

Se hai bisogno che il 🐙👩‍🦼🦖 **personaggio principale** aspetti finché l' 🎂🎾🎁 **oggetto interessante** faccia qualcosa, aggiungi un blocco `attendi`{:class="block3control"}.

![Uno sfondo desertico con una roccia che si muove avanti e indietro.](images/bear.gif)

Potresti usare i blocchi `dire`{:class="block3looks"} o `pensa`{:class="block3looks"}, o anche usare l'estensione `Da Testo a Voce`{:class="block3extensions"} per far parlare il personaggio ad alta voce!

[[[scratch3-text-to-speech]]]

Il personaggio potrebbe esprimere emozioni, come nel progetto [Conversazione spaziale](https://projects.raspberrypi.org/it-IT/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

Il personaggio potrebbe essere coraggioso e avvicinarsi per controllare l'oggetto.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde per testare il tuo progetto. Il 🐙👩‍🦼🦖 **personaggio principale** dovrebbe mostrare curiosità per l'oggetto.

Clicca sulla bandierina verde di nuovo. Se hai cambiato la posizione o l'aspetto dell'🎂🎾🎁 **oggetto interessante** o del 🐙👩‍🦼🦖 **personaggio principale**, dovrai assicurarti che siano riportati alla posizione e all'aspetto iniziale quando esegui nuovamente il progetto.

--- collapse ---
---
title: Imposta la posizione e l'aspetto iniziali di uno sprite
---

Scegli i blocchi di cui hai bisogno per impostare la posizione e l'aspetto di uno sprite all'inizio.

```blocks3
when flag clicked // aggiungi blocchi per impostare l'inizio
switch costume to [costume1 v]
set size to (100) % // dimensione iniziale
go to x: (-200) y: (50) // posizione iniziale
point in direction [90]
set [brightness v] effect to [80]
show
```

**Suggerimento:** Tutti gli effetti grafici vengono cancellati quando si fa clic sulla bandierina verde, quindi non è necessario cancellarli, ma potrebbe essere necessario impostare gli effetti che vuoi dare al tuo sprite.

--- /collapse ---

--- /task ---

--- task ---

**Debug:**

--- collapse ---
---
title: Il suono non funziona
---

Controlla che il volume del tuo computer o tablet sia sufficientemente alto e che gli altoparlanti o le cuffie siano collegati e funzionino correttamente.

--- /collapse ---

--- collapse ---
---
title: La mia animazione non si ripristina in maniera corretta quando clicco sulla bandierina verde
---

Controlla che il tuo progetto abbia uno script con il blocco iniziale `quando si clicca sulla bandierina verde`{:class="block3events"} per gli sprite che ne hanno bisogno e controlla che ripristinino la posizione, la dimensione e l'aspetto degli sprite. Se hai bisogno di un aiuto, guarda l'attività **Imposta la posizione iniziale e l'aspetto iniziali di uno sprite** qui sopra.

--- /collapse ---

--- /task ---

