# Genspark活用研修｜編集可能HTML＋トークスクリプト

Googleスライドの全44ページを、ブラウザで共有・編集できるHTMLにしたものです。各ページのスピーカーノートを、トークスクリプトとして同じ画面に表示します。

## 公開ページ

https://mazua1009-cyber.github.io/editable-five-elements-slide/

特定ページを共有するときは、URL末尾に `#slide=17` のようにページ番号を付けます。

## コード一式を共有

- GitHub：https://github.com/mazua1009-cyber/editable-five-elements-slide
- ZIPダウンロード：https://github.com/mazua1009-cyber/editable-five-elements-slide/archive/refs/heads/main.zip

受け取った人は、ZIPを展開して `index.html` を開けば、スライドとトークスクリプトをブラウザで確認できます。

## 画面上でできること

- 前後ボタン、矢印キー、スペースキーでページ送り
- `全44枚`からページ一覧を表示
- `スライドを編集`で文字を直接編集
- 編集モードで画像をクリックして差し替え
- 右側のトークスクリプトを直接編集
- `HTML保存`で、スライドと台本をまとめて保存
- `台本保存`で、トークスクリプトだけをMarkdown形式で保存
- `全画面`で投影表示

## ファイル

- `index.html`：全44ページのスライドビューアとトークスクリプト
- `talk-script.md`：全ページ分のトークスクリプト
- `assets/`：スライド内で使用する画像

## GitHub Pages

`main`ブランチへ更新を送ると、`.github/workflows/pages.yml`によって公開ページへ自動反映されます。
