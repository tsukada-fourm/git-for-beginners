
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