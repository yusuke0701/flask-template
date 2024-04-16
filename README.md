# TODOアプリをFlaskで作ってみる

## 環境構築メモ

1. devcontainer の導入
   1. 構成ファイル
      1. コンテナイメージ
         1. Python 3
      2. 追加する機能
         1. poetry
2. `poetry init` の実行
3. `poetry config virtualenvs.in-project true --local` の実行
4. README.md の追加
5. 拡張機能の追加
   1. `ms-python.python`
   2. `ms-python.black-formatter`
   3. `yzhang.markdown-all-in-one`
6. vscode の設定ファイルを用意
   1. `mkdir .vscode` の実行
   2. `.vscode/settings.json` の実行
   3. `editor.formatOnSave` を有効にする
7. poetry add flask

## ローカルサーバーの立ち上げ

`poetry run python app.py`
