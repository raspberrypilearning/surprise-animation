## 好奇心を示す

オブジェクトは何か興味をひくようなことをしますか？ 主人公はどのように反応するでしょう？ あなたが決めるのです！ アニメーションの**パート2**を作成しましょう。

![3つのフレームのフィルムストリップ。 2番目のフレームが強調表示されている。 主人公が奇妙なオブジェクトを見ながら「うーん」と考えている場面が描かれているフレーム。](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**分解**</span>とはプロジェクトをより小さく、理解しやすい部品に分けることです。 つまり、一度に一部分ずつ構築して、プロジェクトを完成させることができるということです。 このステップでは、アニメーションの好奇心の部分のみに焦点を当てます。
</p>

### オブジェクト

--- task ---

**選択:** 🎂🎾🎁**面白いオブジェクト** に何かをさせて注意をひきたいなら、オブジェクトが行うことを選びます。

![岩が前後に揺れている砂漠の背景。](images/jiggle.gif)

🎂🎾🎁**興味をひくオブジェクト**の`緑の旗が押されたとき`{:class="block3events"}設定スクリプトの最後にブロックを追加します。

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### 主人公

--- task ---

🐙👩‍🦼🦖**主人公** がオブジェクトに興味を示すようにします。 🐙👩‍🦼🦖**主人公**の設定スクリプトの最後にブロックを追加します。

🎂🎾🎁**面白いオブジェクト**が何かを実行するまで🐙👩‍🦼🦖**主人公**を待機させる必要があるなら、`待つ`{:class="block3control"}ブロックを追加します。

![岩が前後に揺れている砂漠の背景。](images/bear.gif)

`言う`{:class="block3looks"}や`考える`{:class="block3looks"}ブロック、または`音声合成`{:class="block3extensions"}拡張機能を使って主人公に声を出させることができます！

[[[scratch3-text-to-speech]]]

[スペーストーク](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"}プロジェクトのように、主人公に感情を表現させることもできます。

[[[scratch3-change-costumes-to-show-mood]]]

主人公が果敢にオブジェクトに近いてオブジェクトを確かめることもできます。

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**テスト:** 緑の旗をクリックしてプロジェクトをテストします。 🐙👩‍🦼🦖**主人公**はオブジェクトに好奇心を示すはずです。

緑の旗をもう一度クリックします。 🎂🎾🎁**面白いオブジェクト**または🐙👩‍🦼🦖**主人公**のスプライトの位置や見た目を変更した場合は、プロジェクトを再度実行したときに、最初の位置と見た目に戻っていることを確認する必要があります。

--- collapse ---
---
title: Set the starting position and looks for a sprite
---

開始時にスプライトの位置と見た目を設定するブロックを選択します。

```blocks3
when flag clicked // add blocks to set up the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**ヒント:** 緑の旗をクリックされるとすべてのグラフィック効果はクリアされるので、あなたがクリアする必要はありませんが、スプライトが持っていて欲しい効果を設定する必要があるかもしれません。

--- /collapse ---

--- /task ---

--- task ---

**デバッグ**

--- collapse ---
---
title: The sound is not working
---

コンピューターまたはタブレットの音量が十分に大きいこと、およびスピーカーまたはヘッドホンが接続されて正しく機能していることを確認します。

--- /collapse ---

--- collapse ---
---
title: My animation does not reset properly when I click on the green flag
---

必要なスプライトの`緑の旗が押されたとき`{:class="block3events"}スクリプトがプロジェクトにあり、スプライトの位置、大きさ、見た目をリセットしていることを確認します。 詳しくは、上にある**スプライトの開始位置と開始時のコスチュームを設定する**タスクを参照してください。

--- /collapse ---

--- /task ---

