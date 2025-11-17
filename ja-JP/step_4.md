## サプライズを加える！

ここで、サプライズを追加する必要があります。 オブジェクトに何が起きたらよいでしょうか？
- 別のオブジェクトになりますか？
- 主人公になりますか？
- 消えて別のスプライトを出現させますか？

あなたが決めるのです！ アニメーションの**パート3**を作成しましょう。

![3つのフレームのフィルムストリップ。 3番目のフレームが強調表示されている。 フレームには、オブジェクトに驚いているキャラクターのシーンが描かれている。](images/surprise.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
どんでん返しや驚きのある物語を書いたことがありますか？ 終わりの予測できないショーを見たり、本を読んだりしたことがありますか？ デジタルストーリーやアニメーションを作成するときにも同じ方法が使えます。 
</p>

### サプライズはいつ起こりますか？

--- task ---

🎂🎾🎁**興味をひくオブジェクト**のスプライトを選択します。 スクリプトを追加して、希望するタイミングでサプライズが始まるようにします。

あなたのプロジェクトに適した遅延時間を選ぶ必要があります。 長い時間を使って好奇心をあおる主人公の場合は、より長い遅延を選ぶ必要があるでしょう。

```blocks3
when flag clicked
wait (5) seconds // change the number to create your time delay
```

--- /task ---

### さあ、サプライズを作りましょう！

--- task ---

オブジェクトは、 `音を鳴らす`{:class="block3sound"}、 `コスチュームを◯にする`{:class="block3looks"}、 `画像効果を変更`{:class="block3looks"}、または `大きさを変更`{:class="block3looks"}。

スプライトに意外なコスチュームを追加すると、スプライトは`コスチューム`{:class="block3looks"}をそれに切り替えて表示できます。

![岩が前後に揺れている砂漠の背景。](images/bat.gif)

[[[scratch3-add-costumes-to-a-sprite]]]

`音量`{:class="block3events"}ブロックの `タイマー`{:class="block3events"}オプションを選択していることを確認してください。

--- collapse ---
---
title: Hide and show sprites
---

🎂🎾🎁**興味をひくオブジェクト**スプライト
```blocks3
when flag clicked
show
wait (5) seconds
hide
```

🎷👻⚡**サプライズオブジェクト**スプライト
```blocks3
when flag clicked
hide
wait (5) seconds
show
```

**ヒント:** 🎷👻⚡**サプライズオブジェクト**スプライトを`表示する`{:class="block3looks"}場合、`緑の旗が押されたとき`{:class="block3events"}にそれを`隠す`{:class="block3looks"}必要があります。

--- /collapse ---

--- /task ---

--- task ---

**テスト:** 緑色の旗をクリックします。 サプライズは適切なタイミングで起こりますか？ アニメーションは正しくリセットされますか？

--- /task ---

--- task ---

**デバッグ**

スプライトを別のスプライトの前や後に配置する必要がある場合は、レイヤーを使用できます。

[[[scratch3-positioning-with-layers]]]

サプライズが間違ったタイミングで起こった場合は、次の方法で修正できます。

--- collapse ---
---
title: The surprise starts at the wrong time
---

タイミングを正しくするために、一部またはすべての`待つ`{:class="block3control"}ブロックの秒数を変更するか、`待つ`{:class="block3control"}ブロックをもっと追加する必要があるかもしれません。

--- /collapse ---

--- /task ---

