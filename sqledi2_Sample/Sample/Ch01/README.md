# データベースとは

## RDBMS
Relational Database Management System

多数のクライアントから要求を受け取るほかにも、大量のデータを保管しているデータベースを処理する必要があるため、クライアントを動かすコンピュータよりも高性能なコンピュータを使用する。

## RDBMSのシステム構成
1. クライアントからRDBMSにSQL発行
2. サーバのRDBMSがSQLを元にデータの読み書きをする。
3. RDBMSがクライアントに要求データを返したり、データベースのデータを書き換える。

## 標準SQL
SQLごとに方言があるが、標準SQLはどのデータベースでも使える。  

## 命名ルール
- 半角のアルファベット
- 半角の数字
- アンダーバー
- 名前の最初の文字は「半角のアルファベット」にする
- 名前は重複してはならない

## データ型の指定
- INTEGER
  - 小数は入れることができない

- CHAR
  - 固定長文字列

- VARCHAR
  - 可変超文字列
  - varは可変という意味
