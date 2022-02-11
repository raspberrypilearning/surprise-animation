## 好奇心

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
注意を引くために、オブジェクトは何かをしますか？ 主人公はどのように反応しますか？

あなたが決める！
</div>
<div>

！[「BOO！」好奇心旺盛な主人公を描いたプロジェクト。]（images / boo.png）

</div>
</div>

### オブジェクト

--- task ---

**選択：** オブジェクトに何かを実行させたい場合は、オブジェクトが実行することを選択します。

**オブジェクトの** `緑の旗が押された時`{：クラス=「block3events」}のセットアップスクリプトの最後に、ブロックを追加します。

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### 主人公

--- task ---

主人公がオブジェクトに興味を示すように仕向けます。 **主人公の** セットアップスクリプトの最後にブロックを追加します。

オブジェクトが何かを実行するまで主人公が待機する必要がある場合は、 `待つ`{：class = "block3control"}ブロックを追加します。

あなたは`言う`{:class="block3looks"}や`考える`{:class="block3looks"}ブロック、または `音声合成`{:class="block3extensions"}拡張機能を使って主人公に声を出させることができます！

[[[scratch3-text-to-speech]]]

主人公は[スペーストーク](https://projects.raspberrypi.org/en/projects/space-talk){:target="_blank"}プロジェクトのように感情を表すことができます。

[[[scratch3-change-costumes-to-show-mood]]]

主人公は勇敢で、オブジェクトを確認するために近づくことができます。

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**テスト：** 緑のフラグをクリックして、プロジェクトをテストします。 主人公はオブジェクトに好奇心を示すはずです。

緑の旗をもう一度クリックします。 **オブジェクト** または **主人公** スプライトの位置またはコスチュームを変更した場合は、プロジェクトを再度実行するときに、それらが開始位置や開始時のコスチュームに戻っていることを確認する必要があります。

--- collapse ---
---
title: スプライトの開始位置と開始時のコスチュームを設定する
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
title: 音が出ない
---

コンピューターまたはタブレットの音量が十分に大きいこと、およびスピーカーまたはヘッドホンが接続されて正しく機能していることを確認します。

--- /collapse ---

--- collapse ---
---
title: 緑の旗をクリックすると、アニメーションが正しくリセットされません
---

あなたのプロジェクトが `緑の旗が押された時`{:class="block3events"}を持っていて、スプライトの位置、大きさ、コスチュームをリセットすることを確認します。 詳しくは **スプライトの開始位置と開始時のコスチュームを設定する**タスクを参照してください。

--- /collapse ---

--- /task ---

--- save ---
