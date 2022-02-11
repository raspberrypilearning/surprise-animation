## サプライズ

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
今、あなたはサプライズを追加する必要があります。 オブジェクトはどうなりますか？ 
-別のオブジェクトになりますか？ 
- 主人公になりますか？ 
- 消えて別のスプライトにしますか？ 

あなたが決める！
</div>
<div>

![驚きを示す「猫の魔法」プロジェクト。](images/cat-magic.png)

</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
どんでん返しや驚きのある物語を書いたことがありますか？ ショーを見たり、終わりが予測できない本を読んだりしたことがありますか？ デジタルストーリーやアニメーションを作成するときも同じ方法を使用できます。 
</p>

### サプライズはいつ起こりますか？

--- task ---

**オブジェクト** スプライトを選択します。 スクリプトを追加して、必要なときにサプライズを開始できるようにします。

プロジェクトに適した時間遅延を選択する必要があります。 好奇心をそそるのに長い時間を費やす主人公がいる場合は、より長い遅延を選択する必要があります。

[[[scratch3-time-delay]]]

--- /task ---

### さあ、サプライズを作りましょう！

--- task ---

オブジェクトは、 `音を鳴らす`{:class="block3sound"}、 `コスチュームを◯にする`{:class="block3looks"}、 `画像効果を変更`{:class="block3looks"}、または `大きさを変更`{:class="block3looks"}。

スプライトに意外なコスチュームを追加すると、スプライトは`コスチューム`{:class="block3looks"}をそれに切り替えて表示できます。 たとえば、あなたは **りんご**が**お化け**になるようにすることもできます。

[[[scratch3-add-costumes-to-a-sprite]]]

スプライトを別のスプライトに変化するようにすることもできます。これを行うには、**オブジェクト**を`隠す`{:class="block3looks"} と同時に 別のスプライトを`表示`{:class="block3looks"} します。

--- collapse ---
---
title: スプライトの表示と非表示
---

**オブジェクト** スプライト：   
```blocks3
when [timer v] > (4) // 遅れを設定する
hide
```

**サプライズ** スプライト：
```blocks3
when [timer v] > (4) // 同じ遅れ
show
```

**ヒント：** もし**サプライズ** スプライトを `表示`{:class="block3looks"} する場合、 `緑の旗が押された`{:class="block3events"}ときにそのスプライトを`隠す`{:class="block3looks"}必要があります。

--- /collapse ---

--- /task ---

--- task ---

**テスト：** 緑色の旗をクリックします。 サプライズは適切なタイミングで起こりますか？ アニメーションは正しくリセットされますか？

--- /task ---

--- task ---

**デバッグ：**

スプライトを別のスプライトの前または後ろに配置する必要がある場合は、レイヤーを使用できます。

[[[scratch3-positioning-with-layers]]]

サプライズが起こるタイミングが悪ければ、それを修正します。

--- collapse ---
---
title: タイマースクリプトが間違った時間にサプライズを開始する
---

`音量`{:class="block3events"}ブロックの `タイマー`{:class="block3events"}オプションを選択していることを確認してください。

```blocks3
when [timer v] > [5]
```

`タイマー`{:class="block3events"}が正しく選択されている場合は、タイマーが待機する時間を調整してみてください。

--- /collapse ---

--- /task ---

--- save ---
