
FizzBuzz問題を段階的にcommitしながらソースを完成させよう

※レベル別対応
for/while禁止
Java 21 のVirtual Thread検証

----
このハンズオンにおけるルール
新しいprojectを作成しgit repositoryの作成を行う。
step1という名前のbranchを作成し作業を開始する。
step2以降はその前のbranchから新しいbranchを作成して作業を開始する。

※レベル別対応
各stepごとに作業者を変えていく。

### step1
1. 1から30の数字を1行ずつ表示して

### step2

1. 1から30の数字を1行ずつ表示して
1. 3の倍数を表示するときは、Fizzを表示して

----

### step3

1. 1から30の数字を1行ずつ表示して
1. 3の倍数を表示するときは、Fizzを表示して

### step4

1. 1から30の数字を1行ずつ表示して
1. 3の倍数を表示するときは、Fizzを表示して
3. 5の倍数を表示するときは、Buzzを表示して

### step5

1. 1から30の数字を1行ずつ表示して
1. 3の倍数を表示するときは、Fizzを表示して
3. 5の倍数を表示するときは、Buzzを表示して
4. ただし3の倍数 かつ 5の倍数の場合はFizzBuzzを表示して

----

ここからは追加対応

1. printlnの処理を1つの関数にする。
2. 1から30までの数字を逆順にする。
3. 他の処理についてprintln同様に関数にしていく。
4. 数字を出力する時にそれよりも前に出力した数字も合わせて表示して
 ```
 1
 2(1)
 Fizz
 4(2)
 ```
5. テストクラスを作成する。
