custom-NewTab - Chrome Extension
====

Chrome拡張機能で新規タブを開いたときに表示されるHTMLを変更する最小構成のテンプレート

## Usage
* `extension/manifest.json`を開き、変更したい箇所を適当に変える。
* `extension/newtab.html`の中身を適当なhtmlに置き換える。
    - 必要に応じてJSやCSSを追加する
* `extension`ディレクトリを拡張機能として読み込ませる。

## Install
[chrome://extensions/](chrome://extensions/)より

* 方法1
    + `パッケージ化されていない拡張機能を読み込む...`
    + `extension`ディレクトリを指定
    + 完了

* 方法2
    + `extension.crx`を拡張機能のタブにドラッグ・アンド・ドロップ
    + 完了

## Licence
[WTFPL](http://www.wtfpl.net/)