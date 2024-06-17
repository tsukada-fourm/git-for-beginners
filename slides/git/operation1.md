

gitで変更を行うための基本操作として、いくつかのコマンドと流れを覚える

まずサーバーからデータを共有しローカル上で操作できる状態を作成する。

```
git clone https://github.com/tsukada-fourm/start-git.git
cd start-git
git switch -c <みなさんの名前>
```

![vscode上でコマンド1](images/github/lecture/1.png)

----

#### git clone

GitHubに共有されているリモートリポジトリーを個々のPCに複製する。

#### git switch

今あるブランチから新しい分岐を作成する。

----

新しく作成したブランチで編集を行う。

**お題**
好きなxxx(食べ物/飲み物/遊びetc)をlike.txtに記載する。
