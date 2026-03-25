--- question ---
---
legend: 質問2/3
---

あなたのプロジェクトで、あなたは`タイマー`{:class="block3events"}または `待機`{:class="block3control"} ブロックでアニメーションを計画しました。

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

このスクリプトでは、小さな恐竜を表示するためにユーザーの操作が必要です。

  --- /feedback ---

- ( )
```blocks3
when flag clicked
show
wait [6] seconds
```

  --- feedback ---

 タイマーが6秒待つと、小さな恐竜が現れて大きな恐竜を驚かせます！

  --- /feedback ---

- (x)
```blocks3
when flag clicked
wait [6] seconds
show
```

  --- feedback ---

 ここでは、小さな恐竜が大きな恐竜を驚かせてから、6秒間待ちます。

  --- /feedback ---

--- /choices ---

--- /question ---
