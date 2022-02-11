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
when [loudness v] > (6)
show
```

  --- feedback ---

 これらは適切なブロックですが、 ドロップダウンメニューで`音量`{:class="block3events"}の代わりに、`タイマー`{:class="block3events"}を選択する必要があります。

  --- /feedback ---

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
wait (6) seconds
```

  --- feedback ---

 ここでは、小さな恐竜が大きな恐竜を驚かせてから、6秒間待ちます。

  --- /feedback ---

- (x)
```blocks3
when [timer v] > (6)
show
```

  --- feedback ---

 タイマーが6秒待つと、小さな恐竜が現れて大きな恐竜を驚かせます！

  --- /feedback ---

--- /choices ---

--- /question ---
