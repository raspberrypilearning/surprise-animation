## Montrer de la curiosité

L'objet fera-t-il quelque chose pour attirer l'attention ? Comment réagira le personnage ? C'est toi qui décides ! Crée la **seconde partie** de ton animation.

![Une bande de film avec 3 images. La seconde image est mise en surbrillance. L'image montre une scène avec un personnage pensant "hmmmm" tout en regardant un objet curieux.](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**Décomposition**</span> consiste à décomposer un projet en parties plus petites et plus faciles à comprendre. Cela signifie que tu peux construire un projet une partie à la fois jusqu'à ce que tu l'aies terminé. Dans cette étape, tu te concentreras uniquement sur la partie curiosité de ton animation.
</p>

### L’objet

--- task ---

**Choisir :** Si tu veux que l' 🎂🎾🎁 **objet intéressant** fasse quelque chose pour attirer l'attention, choisis ce que l'objet fera.

![Un arrière-plan désertique avec un rocher oscillant d'avant en arrière.](images/jiggle.gif)

Ajoute des blocs à la fin du script de configuration de 🎂🎾🎁 **l'objet intéressant** `quand le drapeau vert est cliqué`{:class="block3events"}.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### Le personnage

--- task ---

Fais en sorte que le 🐙👩‍🦼🦖 **personnage principal** s'intéresse à l'objet. Ajoute des blocs à la fin du script de configuration du 🐙👩‍🦼🦖 **personnage principal**.

Si tu as besoin que le 🐙👩‍🦼🦖 **personnage principal** attende que l' 🎂🎾🎁 **objet intéressant** ait fait quelque chose, ajoute un bloc `attendre`{:class="block3control"}.

![Un arrière-plan désertique avec un rocher oscillant d'avant en arrière.](images/bear.gif)

Tu peux utiliser les blocs `dire`{:class="block3looks"} ou `penser`{:class="block3looks"}, ou même utiliser l’extension `Synthèse vocale`{:class="block3extensions"} pour que le personnage puisse parler oralement !

[[[scratch3-text-to-speech]]]

Le personnage pourrait émouvoir, comme dans le projet [Parler de l'espace](https://projects.raspberrypi.org/fr-FR/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

Le personnage pourrait être courageux et se rapprocher pour vérifier l'objet.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert pour tester ton projet. Le 🐙👩‍🦼🦖 **personnage principal** doit montrer de la curiosité pour l'objet.

Clique à nouveau sur le drapeau vert. Si tu as changé la position ou l'apparence du sprite 🎂🎾🎁 **objet intéressant** ou 🐙👩‍🦼🦖 **personnage principal**, tu devras t'assurer qu'ils sont remis à leur position ou apparence de départ lorsque tu exécutes à nouveau le projet.

--- collapse ---
---
title: Définir la position de départ et rechercher un sprite
---

Choisis les blocs dont tu as besoin pour définir la position et recherche un sprite au début.

```blocks3
when flag clicked // ajoute des blocs pour configurer le départ 
switch costume to [costume1 v]
set size to (100) % // taille de départ
go to x: (-200) y: (50) // position de départ
point in direction [90]
set [brightness v] effect to [80]
show
```

**Astuce :** tous les effets graphiques sont effacés lorsque tu cliques sur le drapeau vert, tu n'as donc pas besoin de les effacer, mais tu devras peut-être définir les effets souhaités pour ton sprite.

--- /collapse ---

--- /task ---

--- task ---

**Déboguer :**

--- collapse ---
---
title: Le son ne fonctionne pas
---

Vérifie que le volume de ton ordinateur ou de ta tablette est suffisamment fort et que tes haut-parleurs ou tes écouteurs sont connectés et fonctionnent correctement.

--- /collapse ---

--- collapse ---
---
title: Mon animation ne se réinitialise pas correctement lorsque je clique sur le drapeau vert
---

Vérifie que ton projet a des scripts `quand le drapeau vert est cliqué`{:class="block3events"} pour les sprites qui en ont besoin, et vérifie qu'ils réinitialisent la position, la taille et l'apparence pour les sprites. Pour obtenir de l'aide, consulte la tâche **Définir la position de départ et l'apparence pour un sprite** ci-dessus.

--- /collapse ---

--- /task ---

