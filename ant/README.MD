## Antとは？

プログラムやプロジェクトのビルド支援ツール。
XMLファイルにつらつらとやること書いていって、コマンド一発で面倒な一連の操作を再現できるようにする。
Javaプロジェクトでよく使われていた。

参照

http://ant.apache.org/

## 実際のところ

2000年代から古くからのJavaの友達であるが、リポジトリ関連の機能も取り込んだ構成管理ツールMavenにお株を取られることとなった。

が、mavenと違いローカルマシンだけですべてが完結するため、レガシーJavaを好みそうな上長の許可が不要だったりと使いどころはあるっちゃある。
（しかも滅茶苦茶単純なため、通しやすい）

## 注意点など

だいたい、Javaのコンパイルに`javac`を実行するが、Eclipseのコンパイルとは違ったバイナリができあがる・・・。
（向こうはどうやらCompileAPIかなにかを使っているみたいだ）
風通しの悪い組織にありがちなバイナリの差分確認がどうのこうのに引っかかる。面倒くさいので注意だ。
