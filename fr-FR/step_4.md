## Surprise

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Maintenant, tu dois ajouter une surprise. Que peut-il arriver à l'objet ? 
- Se transformera-t-il en un autre objet ? 
- Est-ce qu'il va devenir un personnage ? 
- Va-t-il disparaître et révéler un autre sprite ? 

Tu décides!
</div>
<div>

![Le projet 'Cat magic' montrant la surprise.](images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
As-tu écrit une histoire avec un rebondissement ou une surprise ? As-tu regardé une émission ou lu un livre dont la fin est imprévisible ? Tu peux utiliser les mêmes méthodes lorsque tu crées une histoire ou une animation numérique. 
</p>

### A quand la surprise ?

--- task ---

Sélectionne le sprite d'**objet**. Ajoute un script pour que la surprise commence quand tu le souhaites.

Tu dois choisir un délai qui convient à ton projet. Si tu as un personnage qui passe beaucoup de temps à être curieux, tu devras choisir un délai plus long.

[[[scratch3-time-delay]]]

--- /task ---

### Maintenant, crée la surprise !

--- task ---

L'objet pourrait `jouer un son`{:class="block3sound"}, `basculer sur le costume`{:class="block3looks"}, `changer les effets graphiques`{:class="block3looks"}, ou `changer la taille`{:class="block3looks"}.

Tu peux ajouter un costume surprenant au sprite, alors le sprite pourrait `basculer sur le costume`{: class = « block3looks »} pour le révéler. Par exemple, tu peux transformer la **pomme** en **fantôme**.

[[[scratch3-add-costumes-to-a-sprite]]]

Tu peux faire en sorte que le sprite semble se transformer en un sprite différent — pour ce faire, `cacher`{:class="block3looks"} l'**objet** sprite en même temps que tu `montres`{:class="block3looks"} un autre sprite.

--- collapse ---
---
title: Masquer et afficher les sprites
---

Le sprite **objet**:
```blocks3
when [timer v] > (4) // régler le délai
hide
```

Un sprite **surprise**:
```blocks3
when [timer v] > (4) // même retard
show
```

**Astuce :** Si tu fais un `montrer`{:class="block3looks"} le sprite **surprise**, tu devras le `cacher`{:class="block3looks"} `quand le drapeau vert est cliqué`{:class="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert. La surprise arrive-t-elle au bon moment ? L'animation se réinitialise-t-elle correctement ?

--- /task ---

--- task ---

**Déboguer:**

Si tu as besoin qu'un sprite soit devant ou derrière un autre sprite, tu peux utiliser des calques :

[[[scratch3-positioning-with-layers]]]

Si la surprise se produit au mauvais moment, tu peux y remédier :

--- collapse ---
---
title: Les scripts de minuterie déclenchent la surprise au mauvais moment
---

Assure-toi d'avoir sélectionné le `chronomètre`{:class="block3events"} dans le bloc `quand le volume sonore`{:class="block3events"} :

```blocks3
when [timer v] > [5]
```

Si tu as le `chronomètre`{:class="block3events"}, essaye d'ajuster le temps d'attente du minuteur.

--- /collapse ---

--- /task ---

--- save ---
