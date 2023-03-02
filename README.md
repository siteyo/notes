# notes

文章作成のためのTextlint設定テンプレート。

## 必要なもの

- Node.js
- テキストエディタ

## インストール方法

```bash
npm install
```

エディタでTextlintを使用するための設定は各自で行ってください。

## 使い方

`doc`ディレクトリ配下にチェックしたいMarkdownファイルを作成し、文章を書くだけ。

## 作者の使い方

作者の環境は以下の通りです。

- OS
  - Windows (WSL:Ubuntu)
- テキストエディタ
  - [NeoVim](https://neovim.io/)
- その他
  - [asdf](https://asdf-vm.com/)（Node.jsのバージョン管理用）
  - [mind.nvim](https://github.com/phaazon/mind.nvim)（メモ取り、タスクを整理するNeoVimプラグイン）
  - [null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim)（エディタでTextLintを使用するためのNeoVimプラグイン）

mind.nvimを使用するとツリー構造でメモやタスクを管理できます。
ツリーのルート配下に以下の項目を作成し管理しています。

-  Tasks
  -  Not Started
  -  Active
  -  Active, but paused
  -  Completed
-  Meeting
-  Dairy
- ﮷ Documents
