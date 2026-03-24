## 好奇心を示す

オブジェクトは何か興味をひくようなことをしますか？ 主人公はどのように反応するでしょう？ あなたが決めるのです！ アニメーションの**パート2**を作成しましょう。

![3つのフレームのフィルムストリップ。 2番目のフレームが強調表示されている。 主人公が奇妙なオブジェクトを見ながら「うーん」と考えている場面が描かれているフレーム。](images/curiosity.png)

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
  <span style="color: #0faeb0">**分解**</span>とはプロジェクトをより小さく、理解しやすい部品に分けることです。 つまり、一度に一部分ずつ構築して、プロジェクトを完成させることができるということです。 このステップでは、アニメーションの好奇心の部分のみに焦点を当てます。
</p>

### オブジェクト

--- task ---

**選択：** オブジェクトに何かを実行させたい場合は、オブジェクトが実行することを選択します。

![岩が前後に揺れている砂漠の背景。](images/jiggle.gif)

**オブジェクトの** `緑の旗が押された時`{:class="block3events"}のセットアップスクリプトの最後に、ブロックを追加します。

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### キャラクター

--- task ---

🐙👩‍🦼🦖**主人公** がオブジェクトに興味を示すようにします。 主人公がオブジェクトに興味を示すように仕向けます。 **主人公の** セットアップスクリプトの最後にブロックを追加します。

オブジェクトが何かを実行するまで主人公が待機する必要がある場合は、 `待つ`{:class="block3control"}ブロックを追加します。

![岩が前後に揺れている砂漠の背景。](images/bear.gif)

あなたは`言う`{:class="block3looks"}や`考える`{:class="block3looks"}ブロック、または `音声合成`{:class="block3extensions"}拡張機能を使って主人公に声を出させることができます！

[[[scratch3-text-to-speech]]]

主人公は[スペーストーク](https://projects.raspberrypi.org/ja-JP/projects/space-talk){:target="_blank"}プロジェクトのように感情を表すことができます。

[[[scratch3-change-costumes-to-show-mood]]]

主人公は勇敢で、オブジェクトを確認するために近づくことができます。

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**テスト：** 緑のフラグをクリックして、プロジェクトをテストします。 主人公はオブジェクトに好奇心を示すはずです。 🐙👩‍🦼🦖**主人公**はオブジェクトに好奇心を示すはずです。

緑の旗をもう一度クリックします。 緑の旗をもう一度クリックします。 **オブジェクト** または **主人公** スプライトの位置またはコスチュームを変更した場合は、プロジェクトを再度実行するときに、それらが開始位置や開始時のコスチュームに戻っていることを確認する必要があります。

--- collapse ---
---
title: Set the starting position and looks for a sprite
---

開始時にスプライトの位置とコスチュームを設定するブロックを選択します。

```blocks3
when flag clicked // add blocks to set up the start 
switch costume to [costume1 v]
set size to (100) % // starting size
go to x: (-200) y: (50) // starting position
point in direction [90]
set [brightness v] effect to [80]
show
```

**ヒント：** 緑のフラグをクリックすると、すべてのグラフィックエフェクトがクリアされるため、クリアする必要はありませんが、スプライトに持たせるエフェクトを設定する必要がある場合があります。

--- /collapse ---

--- /task ---

--- task ---

**デバッグ：**

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

あなたのプロジェクトが `緑の旗が押された時`{:class="block3events"}を持っていて、スプライトの位置、大きさ、コスチュームをリセットすることを確認します。 詳しくは **スプライトの開始位置と開始時のコスチュームを設定する**タスクを参照してください。 詳しくは、上にある**スプライトの開始位置と開始時のコスチュームを設定する**タスクを参照してください。

--- /collapse ---

--- /task ---

