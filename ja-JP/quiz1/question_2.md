--- question ---
---
凡例：質問2/3
---

In your project, you controlled your animation with `wait`{:class="block3control"} blocks.

この恐竜プロジェクトでは、小さな恐竜が6秒間待ってから卵から飛び出し、大きな恐竜を驚かせます。

![ステージ上の恐竜のスプライトと卵のスプライト。](images/quiz-q2.png)

**小さな恐竜** スプライトのどのスクリプトがこれを実現しますか？

--- choices ---

- ( )
```blocks3
when this sprite clicked
show
```

  --- feedback ---

This script needs user interaction for the little dinosaur to show.

  --- /feedback ---

- ( )
```blocks3
when flag clicked
show
wait [6] seconds
```

  --- feedback ---

 Here, the little dinosaur surprises the big dinosaur, and then waits 6 seconds.

  --- /feedback ---

- (x)
```blocks3
when flag clicked
wait [6] seconds
show
```

  --- feedback ---

 After 6 seconds, the little dinosaur appears and surprises the big dinosaur!

  --- /feedback ---

--- /choices ---

--- /question ---
