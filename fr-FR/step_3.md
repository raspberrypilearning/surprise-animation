## Curiosité

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
L'objet fera-t-il quelque chose pour attirer l'attention ? Comment réagira le personnage ?

Tu décides!
</div>
<div>

![Le projet « BOO! » montrant le personnage curieux.](images/boo.png)

</div>
</div>

### L’objet

--- task ---

**Choisir :** Si tu veux que l'objet fasse quelque chose, choisis ce que l'objet fera.

Ajoute des blocs à la fin de **l’objet** `quand le drapeau vert est cliqué`{:class="block3events”} le script de configuration.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### Le personnage

--- task ---

Fais en sorte que le personnage principal s'intéresse à l'objet. Ajoute des blocs à la fin du script de configuration du **personnage**.

Si tu as besoin que le personnage attende que l'objet ait fait quelque chose, ajoute un bloc `attendre`{:class="block3control"}.

Tu peux utiliser le blocs `dire`{:class="block3looks"} ou `penser`{:class="block3looks"}, ou même utiliser l’extension de `synthèse vocale`{:class="block3extensions"} pour créer le personnage parle à voix haute !

[[[scratch3-text-to-speech]]]

Le personnage pourrait émouvoir, comme dans le projet [Space talk](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

Le personnage pourrait être courageux et se rapprocher pour vérifier l'objet.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert pour tester ton projet. Le personnage doit montrer de la curiosité à propos de l'objet.

Clique à nouveau sur le drapeau vert. Si tu as modifié l'**objet** ou la position ou l'apparence de sprite de **personnage** , tu devras t'assurer qu'ils sont remis à leur position ou apparence de départ lorsque tu réexécutes le projet.

--- collapse ---
---
title : Définir la position de départ et rechercher un sprite
---

Choisis les blocs dont tu as besoin pour définir la position et recherche un sprite au début.

```blocks3
when flag clicked // add blocks to set up the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**Astuce :** Tous les effets graphiques sont effacés lorsque tu cliques sur le drapeau vert, tu n'as donc pas besoin de les effacer, mais tu devras peut-être définir les effets que tu souhaites que le sprite ait.

--- /collapse ---

--- /task ---

--- task ---

**Déboguer:**

--- collapse ---
---
title : Le son ne fonctionne pas
---

Vérifie que le volume de ton ordinateur ou de ta tablette est suffisamment fort et que tes haut-parleurs ou tes écouteurs sont connectés et fonctionnent correctement.

--- /collapse ---

--- collapse ---
---
title : Mon animation ne se réinitialise pas correctement lorsque je clique sur le drapeau vert
---

Vérifie que ton projet a `quand le drapeau vert est cliqué `{:class="block3events"} scripts pour les sprites qui en ont besoin, et vérifie qu'ils réinitialisent la position, la taille et l'apparence pour les sprites. Pour obtenir de l'aide, consulte le **Définir la position de départ et l'apparence pour un sprite** ci-dessus.

--- /collapse ---

--- /task ---

--- save ---
