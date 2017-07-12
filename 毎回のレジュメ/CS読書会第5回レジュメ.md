# 第5回 C#読書会 2017年7月12日(水)

## 学習範囲

* 70-483 p.34~p.51(書籍版)

## 今日学ぶこと(予定)

* Objective 1.2: Manage multithreading p.34から
* (今回の予習テキストは、著作権の観点からファイルを公開しない)

## 第5回のまとめ 今回得られた成果

* オータガーさんのlock演算子ライブコーディング
    * lockするのは参照型で。(値型はNG)
    * static, const で静的に参照型をもつのもOK

* オータさんのstring-interning

* P.36 Exchange, CompareExchange
    * 実数値ではlockできないから、こういうメソッドを使う

* Listing 1-41 はどうなる？
    * Task t1 が Interlocked.CompareExchange に入れ替わる

#### 開催概要

* 参加者 : 4人

## 第6回に向けた準備

* Objective 1.2 の続き！
    * Canceling tasks は実践的！
    * 通信処理とかでよく使う！
