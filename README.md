# クローン方法

```
$ git clone https://github.com/georgesekkie/exam_pictweet.git
$ bundle
#  データベース関連作成(errorpictweet_developmentという名前で生成)
$ bundle exec rake db:create
$ bundle exec rake db:migrate
# サーバー起動
$ rails s
```

# 問題
①初めのページでエラーがでる(2箇所問題があります)

②tweetがDB に保存されない(2箇所修正点があります)

③Tweetの削除が出来ない
