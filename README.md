# CodeShelf - Git 練習用 Rails アプリ

このリポジトリは、Rails アプリを題材に Git の基本操作を練習するための教材です。

主に次の流れを練習します。

- ファイルを変更する
- `git status` で状態を見る
- `git diff` で変更内容を見る
- `git add ファイル名` で commit に含める変更を選ぶ
- `git commit -m "メッセージ"` で変更を記録する
- `git log --oneline` で履歴を見る
- `git push origin main` で GitHub へ送る

## アプリについて

CodeShelf は、技術記事を投稿できる小さな Rails アプリです。

授業では、まず Markdown ファイルを変更し、そのあと Rails の画面文言や見た目を少しずつ変更して、変更ごとに commit と push を行います。

## 起動

Codespaces のターミナルで次を実行します。

```bash
bin/rails db:prepare
bin/rails server
```

ブラウザで `/` または `/articles` を開くと、記事一覧画面が表示されます。

## 注意

このリポジトリは第7週 Git 基礎演習用です。
第6週の CRUD デバッグ演習用リポジトリとは異なり、最初から正常に動く状態です。
