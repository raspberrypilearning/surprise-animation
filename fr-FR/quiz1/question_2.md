--- question ---
---
legend : Question 2 sur 3
---

Dans ton projet, tu as planifié ton animation avec des blocs `chronomètre`{:class="block3events"} ou `attendre`{:class="block3control"}.

Dans ce projet de dinosaure, tu veux que le petit dinosaure attende 6 secondes avant de sortir de l'œuf et de surprendre le grand dinosaure.

![Un sprite de dinosaure et un sprite d'œuf sur la scène.](images/quiz-q2.png)

Quel script pour le sprite **petit dinosaure** ferait cela ?

--- choices ---

- ( )
```blocks3
when [loudness v] > (6)
show
```

  --- feedback ---

 Ce sont les bons blocs à utiliser, mais tu dois sélectionner `chronomètre`{:class="block3events"} au lieu d'`volume sonore`{:class="block3events"} dans le menu déroulant.

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked
show
```

  --- feedback ---

Ce script nécessite une interaction de l’utilisateur pour que le petit dinosaure s'affiche.

  --- /feedback ---

- ( )
```blocks3
when flag clicked
show
wait (6) seconds
```

  --- feedback ---

 Ici, le petit dinosaure surprend le grand dinosaure, puis attend 6 secondes.

  --- /feedback ---

- (x)
```blocks3
when [timer v] > (6)
show
```

  --- feedback ---

 Lorsque le minuteur a attendu 6 secondes, le petit dinosaure apparaît et surprend le grand dinosaure !

  --- /feedback ---

--- /choices ---

--- /question ---
