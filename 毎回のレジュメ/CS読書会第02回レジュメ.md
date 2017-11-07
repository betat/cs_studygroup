# 第2回 C#読書会 2017年6月14日

## 学習範囲

* 70-483 p.6~p.31(書籍版)

## 今日学ぶこと(予定)

* Thread
* Task
* Task<T> 戻り値があるタスク
* Async and Await
* Parallel class
* PLINQ, LINQ
* Concurrent Collection

## 第2回のまとめ 今回得られた成果

* Listing1-1のコード例より
    * 2つのThreadが同時に動くとき、それぞれのThreadが交互に動くかは保証できない。
    * どちらが先に動くかは保証できない。

* Thread と Task
    * Thread を便利に使えるのが Task。Task を推奨。
    * Thread > Thread Pool > Task!!

* async and await
    * 非同期で実行する必要がなかったら、同期的に処理を実行する。(非同期にならない。)
    * Listing1-18はどのように実行される？
        * .Resultがないと result の結果を受け取れない。
        * .Resultから返ってくるのはジェネリック型の何かが返ってくる。
        * (↑学んだことの振り返りの一部として)

* Concurrent Collection
    * thread-safe。しかし。。。↓
    * 現代ではあまり使われない。
    * パフォーマンスが高いのはジェネリック型。パフォーマンス重視でジェネリック型を採用する。

* [小ネタ] C# 7.1から Main() をasyncできるようになって、awaitが使えるようになった。

#### 開催概要

* 参加者:4人

## 第3回に向けた準備

* Objective1.1 総まとめ回を開催します！
    * 飛ばした P.21 PLINQ を読む
    * サンプルコード総確認
    * Objective1.1 Thought Experiment
    * Objective1.1 Objective Summary
    * Objective1.1 Objective Review
