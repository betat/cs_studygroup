# C#勉強会第2回　2017/06/14　オータさん

## 教科書で気になった点・不明点等

### Threads クラス
> The Thread.Join method is called on the main thread to let it wait until the other thread finishes.

### Threads pool
> The creation of a thread, however, is something that costs some time and resources
> "reuse"

### Task
> Queuing a work item to a thread pool can be useful, but it has its shortcomings.
> (略)
> Task, which is an object that represents some work that should be done.

> By default, the Task scheduler uses threads from the thread pool to execute Task.

> Calling Wait is equivalent to calling Join on a thread.

### async and await
> But when doing work that's input/output(I/O)-bound, things go a little differently.

a little differently 話がちょっと違う

- p17 last
> The compiler responds to this by transforming your code into a state machine.

### Concurrent collection
> Blocking collection is in reality a wrapper around other collection types.

## 英単語, 文法

- thread
糸・糸のように細いもの・筋道

- asynchronous, synchronous
非同期、同期
cf. symmetry (左右対称)

p5
- Only when all foreground threads end does the common language runtime (CLR) shut down your application
Only, does で強調。
-> When all foreground threads end, the common language ~

p7
- lambda
ランバダ？ってなった。ラムダ。
cf. bomb

p11 l6
- responsive
すぐ応答する、敏感な
cf. レスポンシブデザイン？？

p11 l7
- offload(V)
押し付ける

p17
- predicament
苦境・窮地

p21 EXAM TIP
- keep in mind ~
心に留めておいて、注意して

p25
- concurrent
同時・同時起こる・一致する
