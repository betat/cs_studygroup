# 第6回 C#読書会 2017年7月26日(水)

## 学習範囲

* 70-483 p.37~p.41(書籍版)

## 今日学ぶこと(予定)

* Objective 1.2: Canceling tasks から
* (今回の予習テキストは、著作権の観点からファイルを公開しない)

## 第6回のまとめ 今回得られた成果

* Listing 1-42 はコード自体が不完全。Listing 1-43 を参照する。
* [疑問] Listing 1-43 で try catch せずに IsCancellationRequested を見ればと同様の結果を得られるか？ -> Token は Task のなかだけで見られるものなので、異なる結果になるかも。

* 1-43のように書かず、ContinueWithを使用して短くかけるのが1-44

* TaskStatus 列挙型
    * https://msdn.microsoft.com/ja-jp/library/system.threading.tasks.taskstatus(v=vs.110).aspx

* 方法: 複数のタスクを継続に連結する
    * https://msdn.microsoft.com/ja-jp/library/dd537612(v=vs.110).aspx

* Task.WaitAny に渡される Task は並列処理。

## 今回学んだ英単語

* appropriate
    * 適切な

* periodically
    * 定期的に、周期的に

* token
    * しるし、象徴、証拠、記念品、形見、証拠品、(地下鉄・バス料金などに用いられる)代用貨幣、トークン、(商品との)引替券

* orchestrate
    * (…を)管弦楽に作曲する、組織化する
    * cf) orchestra: オーケストラ

#### 開催概要

* 参加者 : 5人

## 第7回に向けた準備

* Objective 1.2 の Summary,Review
* Objective 1.3 の Making decisions の終わりまで！
    * 70-483 p.40~p.47(書籍版)
