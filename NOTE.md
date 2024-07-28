# VSCodeのターミナルを使うときは、cmdを使用する。powershellは、npxを打つ必要がある 

# 初期化、package.jsonとpackage-lock.jsonを生成
```cmd
npm init

```

# .gitignoreファイルの設置
```text:.gitignore
/node_modules/

```
# typescriptとts-nodeのインストール
```cmd
npm install -g typescript ts-node
tsc -v
ts-node -v
```

# VSCodeの拡張機能CodeRunnerをインストールする

# 実行はコマンドパレット（Ctrl+Shift+P）を開いて、run codeを選択するか
# 実行するソースを開いて、ショートカット(Ctrl+Alt+N)

# ビルドツールの選定
[JavaScriptビルドツールの整理 各ツールの機能と依存関係](https://zenn.dev/nakaakist/articles/86457bf2908379)
