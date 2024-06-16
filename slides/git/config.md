
### gitを利用するにあたり初期設定で必要なもの

```
git config --global user.name 'ユーザー名'
git config --global user.email 'メールアドレス'
```

--globalオプションは現ユーザー(ログインユーザー)共通の設定。
各プロジェクトごとの場合は --localまたは無記入で設定する。

----
```
git config --global push.default current
git config --global color.ui true
git config --global core.quotepath false
```


----

### 今設定されているものを確認する。
git config -l --global



