# stash

```
// 追跡されているファイルを一時退避させる
$ git stash

// 追跡されていないファイル(新規ファイルとか)も含めて一時退避させる
$ git stash -u

// 退避にコメントをつけられる
$ git stash save コメント


// 退避させたファイルの一覧表示
$ git stash list

// 退避を戻してそれを一覧から削除
$ git stash pop

// stash番号を指定して戻す
$ git stash apply stash番号

// 退避一覧を全部削除
$ git stash clear

// stash番号を指定して削除
$ git stash drop stash番号
```
