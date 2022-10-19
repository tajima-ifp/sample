# README-----

最小構成でのraty4.10サンプル
Ruby 3.1.2, Rails 6.1.7, Raty  4.1.0

## raty用の変更点
* /app/javascript/packs/application.js // 17行目以下

* /app/javascript/packs/raty.js
  * https://github.com/wbotelhos/raty/releases/tag/v4.1.0

* /app/views/homes/top.html.erb // 3行目以下

* /app/assets/images/star-half.png, star-off.png, star-on.png

## その他application.jsを動かす上での変更点
* ターミナルでのjqueryインストール「yarn add jquery」

* /config/webpack/environment.js // 3行目～9行目

* /app/javascript/packs/application.js // 6行目