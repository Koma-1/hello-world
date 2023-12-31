# gitの機能

## ローカルレポジトリでの流れ

1. 変更を保存
2. ステージング
3. コミット

## コマンド

- `git status` gitの状態を確認する

- `git add` ステージングエリアに追加

- `git commit` コミットを実行

- `git log` ログの確認

- `git branch` ブランチの作成

- `git checkout` ブランチの切り替え

- `git merge` ブランチをマージ

## リモートレポジトリを使うときの流れ

1. clone
2. ローカルレポジトリで作業
3. push

## リモートレポジトリを使うときのコマンド

- `git clone` レポジトリをコピー

- `git pull` リモートレポジトリと同期

- `git push` 変更をアップロード

## githubフローの説明

**githubフロー**とは、mainとは別にブランチを作成して、ブランチ上で作成することで、

mainのデータを損失することなく編集することができ、mainでも更新したいときに

編集者の任意のタイミングで更新することも可能となる、ブランチベースのワークフローである。 
