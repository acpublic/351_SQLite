## 特徴
- データベースで一般的なSQL（Structured Query Language）が使える
- SQLを使用することで、データベース内のデータの検索、追加、更新、削除が可能
- トランザクションサポートによるデータ整合性の確保：ACID（Atomicity、Consistency、Isolation、Durability）トランザクションのサポート
- クロスプラットフォームへの対応：Windows、Linux、macOSなど、多くのプラットフォームで動作可能 PCやスマートデバイスなど、さまざまなデバイスでも利用できる

## コマンド
https://www.javadrive.jp/sqlite/ini/index1.html

### データベースの作成(存在する場合は実行)
```
$ sqlite3 construct.db
```
### sqlite_sequenceテーブル
sqlite_sequence テーブルは、SQLite の内部で自動的に作成される特別なテーブルです。
このテーブルは、AUTOINCREMENT キーワードを使用して生成された、各テーブルの整数型のプライマリーキーの値を追跡するために使用されます。

## DB Browser for SQLite
https://ja.ubunlog.com/sqlite-3-y-sqlitebrowser-como-instalarlos-en-ubuntu/

## Android
https://developer.android.com/tools/sqlite3?hl=ja
```
$ adb shell
# sqlite3 /data/data/com.example.google.rss.rssexample/databases/rssitems.db
```
