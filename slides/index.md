# git と GitHub についての新人研修

---
## 1.　目次

FILE: contents.md

---

## 2. はじめに

FILE: introduction.md

---

## git とは

FILE: git.md

----

## Githubについて

FILE: github.md
---

## ハンズオン1 GitHub アカウントの作成

FILE: github/createAccount.md
---
## gitのインストール

FILE: git/install.md
---

## gitの概要

FILE: git/notion.md
---

## gitの基本操作(1)

FILE: operation1.md
----

### gitの基本操作(2)

FILE: operation2.md
--- 

### GitHubの確認

ブランチがどうなったかを確認しよう。


---
## gitの基本操作(3)

### 競合の解決

各々の作成したlike.txtはすべて同列の分岐となっています。
gitのシステムではこのlike.txtを1つのものにしようとした場合に機械的に判断できないため、取りまとめるための作業を人力で行う必要があります。

```
git pull origin main
```

※上のコマンドと同等の動きをするコマンド

```
git fetch origin main
git merge origin/main
```

----
#### git merge
他のブランチの状態をワーキングツリーに反映する。

#### git fetch
ローカルにリモートの最新情報を反映させる。



---
## 今回対象外の用語

追跡ブランチ



---
## 参考サイト

### 基本
1. [git公式 book](https://git-scm.com/book/ja/v2/使い始める-バージョン管理に関して)

### 他研修資料


### 応用

2. [Git が内部でデータを取り扱う方法](https://zenn.dev/username/articles/2022-09-19-8118755d3cd9291907ee)

