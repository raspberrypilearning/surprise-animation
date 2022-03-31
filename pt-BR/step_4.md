## Surpresa

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Agora, você precisa adicionar uma surpresa. O que poderia acontecer com o objeto? 
- Vai se transformar em outro objeto? 
- Vai se transformar em outro objeto? 
- Ele vai desaparecer e revelar outro ator? 

Você decide!
</div>
<div>

![O projeto 'Gato mágico' mostrando a surpresa.](Images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Você escreveu uma história com uma reviravolta na história ou uma surpresa? Você assistiu a um programa ou leu um livro com um final imprevisível? Você pode usar os mesmos métodos ao criar uma história ou animação digital. 
</p>

### Quando vai acontecer a surpresa?

--- task ---

Selecione o **objeto** Ator. Adicione um script para fazer a surpresa começar quando você quiser.

Você precisará escolher um intervalo de tempo adequado para o seu projeto. Se você tem um personagem que passa muito tempo sendo curioso, você precisará escolher um atraso maior.

[[[scratch3-time-delay]]]

--- /task ---

### Agora, crie a surpresa!

--- task ---

O objeto poderia `toque o som`{:class="block3sound"}, `mude para a fantasia`{:class="block3looks"}, `mude os efeitos gráficos`{:class="block3looks"} ou `mude no tamanho`{:class="block3looks"}.

Você poderia adicionar uma fantasia surpreendente ao ator, então o ator poderia `mude para a fantasia`{:class="block3looks"} para revelá-la. Por exemplo, você pode fazer com que uma **Maçã** transforme em um **Fantasma**.

[[[scratch3-add-costumes-to-a-sprite]]]

Você poderia fazer o ator parecer um ator diferente - para fazer isso, `esconda`{:class="block3looks"} os **objetos** ator ao mesmo tempo que você `mostre`{:class="block3looks"} outro ator.

--- collapse ---
---
título: Ocultar e mostrar atores
---

O **objeto** ator:
```blocks3
when [timer v] > (4) // defina o intervalo
hide
```

A ator **surpresa**:
```blocks3
when [timer v] > (4) // mesmo intervalo
show
```

**Dica:** Se você fizer um ator **surpresa** `mostre`{:class="block3looks"}, você precisará torná-lo `esconda`{:class="block3looks"} `quando a bandeira verde for clicada`{:class="block3events"}.

--- /collapse ---

--- /task ---

--- task ---

**Teste:** Clique na bandeira verde. A surpresa acontece na hora certa? A animação é reiniciada corretamente?

--- /task ---

--- task ---

**Depurar:**

Se você precisa que um ator esteja na frente ou atrás de outro ator, você pode usar camadas:

[[[scratch3-positioning-with-layers]]]

Se a surpresa acontecer na hora errada, você pode consertar:

--- collapse ---
---
título: Scripts de cronômetro começam a surpresa na hora errada
---

Certifique-se de ter selecionado a opção `cronômetro`{:class="block3events"} no bloco `quando ruído`{:class="block3events"}:

```blocks3
when [timer v] > [5]
```

Se você tiver `cronômetro`{:class="block3events"} selecionado corretamente, tente ajustar a quantidade de tempo que o cronômetro espera.

--- /collapse ---

--- /task ---

--- save ---
