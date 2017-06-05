# We are javascripters LT会 登壇資料

## スライドの操作方法

方向キーの左右で動きます
なお、**クソ重いです**。**GPUの備わっている文明的なデバイスでご覧ください**

## ビルド方法

```
npm i
npm run build
```

**async/awaitがデフォで使えるNodeのバージョンじゃないと動きません。自分のローカルは7.10.0**

Webサーバーなどを立てて`index.html`を参照してください。　**ファイルスキームでは動きません**


## 使用しているパッケージなど

* grimoirejs <- コアのライブラリ
* grimoirejs-math <- 数学ライブラリ
* grimoirejs-fundamental <- grimoireのレンダラープラグイン
* grimoirejs-forward-shading <- シェーディングやライトのプラグイン
* grimoirejs-gltf <- モデル読み込みプラグイン
* grimoirejs-slide-system(謎) <-今回のスライド作成用に作ったGrimoire用スライド作成プラグイン

その他情報などは、[公式サイト](https://grimoire.gl)にどうぞ。また、OSS活動に興味のある方、ディスカッションだけでも参加したい方は、公式サイトからslackへどうぞお入りください。あと、良いと思ったら[コアレポジトリ](https://github.com/GrimoireGL/GrimoireJS)にスターしといてください。
