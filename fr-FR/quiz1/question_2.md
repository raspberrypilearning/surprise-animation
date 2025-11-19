--- question ---
---
legend : Question 2 sur 3
---

Dans ton projet, tu as contrôlé ton animation avec des blocs `attendre` {:class="block3control"}.

Dans ce projet de dinosaure, tu veux que le petit dinosaure attende 6 secondes avant de sortir de l'œuf et de surprendre le grand dinosaure.

![Un sprite de dinosaure et un sprite d'œuf sur la scène.](images/quiz-q2.png)

Quel script pour le sprite **petit dinosaure** ferait cela ?

--- choices ---

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
wait [6] seconds
```

  --- feedback ---

 Ici, le petit dinosaure surprend le grand dinosaure, puis attend 6 secondes.

  --- /feedback ---

- (x)
```blocks3
when flag clicked
wait [6] seconds
show
```

  --- feedback ---

 Au bout de 6 secondes, le petit dinosaure apparaît et surprend le grand dinosaure !

  --- /feedback ---

--- /choices ---

--- /question ---
