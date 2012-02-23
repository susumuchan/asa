Asagao -- ある草野球チームのブログサイト
========================================

『改訂新版　基礎Ruby on Rails』（株式会社オイアクス、黒田努、佐藤和人著。インプレス・ジャパン刊、2012年）のサンプルアプリケーションです。


動作条件
--------

### Windowsの場合 ###

* Ruby 1.9.3
* DevKit

これらは[RubyInstaller](http://rubyinstaller.org/)からダウンロードできます。

### Mac OS Xの場合 ###

* Xcode
* MacPorts
* Ruby 1.9.3

詳しくは書籍のChapter 1を参照してください。


ダウンロード
------------

https://github.com/oiax/asagao の「Downloads」リンクをクリックし、「Download as zip」リンクをクリックしてください。

ダウンロードされたファイルの名前は oiax-asagao-d874ad4.zip のような形式をしています。
これを適当なフォルダに展開してください。


インストール
------------

コマンドプロンプト（ターミナル）を開き、展開されたソースコードのフォルダにcdコマンドで移動します。そして、以下のコマンドを実行してください。

    bundle install
    rake db:setup RAILS_ENV=production


起動
----

    rails s -e production

ブラウザで http://localhost:3000/ を開くと、ローカルマシン上でアプリケーションが利用できます。
