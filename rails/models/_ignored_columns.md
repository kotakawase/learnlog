# ignored_columns

Active Recordで使用できるメソッドで、データベースから読み込むカラムを無視するために使う。<br>
用途としては、削除したいカラムを段階的に削除する際に使われる。

```ruby
class User < ActiveRecord
  self.ignored_columns = ['email']
end
```

上記のように記述すると、emailカラムはUserモデルのインスタンスで読み書きされないようになる。
