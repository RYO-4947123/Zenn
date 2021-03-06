---
title: "┣ イシューからマージリクエスト作成"
free: false
---

## イシューからマージリクエスト作成

GitLabはイシューを作成しなくてもブランチからマージリクエストを作成することができます。  
ごく小さな修正や緊急の対応ではイシューを作成しない場合もありますが、
原則としてはイシューを作成後にイシューに関連したマージリクエストを作成する事が基本です。

### 作成方法

イシューの詳細情報画面から「マージリクエストを作成（Create merge request）」プルダウンを開きます。  
マージリクエスト作成時に同時に新規ブランチを作成します。この時、ブランチ名にイシューの番号がデフォルトで設定されています。

![](/images/books/497459787cb294/issue_05.png)

:::message
作成するブランチ名はメンバーと話し合って一貫性のある名称になるようにしましょう。
例えば、イシューの分類毎にしたい場合は「feature/~」「bug/~」のようにプレフィックスを付けたりします。
:::

![](/images/books/497459787cb294/issue_06.png)

ほとんどの項目はイシュー作成と同様です。
追加でレビュアー（Reviewer）を設定することができます。

#### マージオプション

- Delete source branch when merge request is accepted.
マージリクエストのマージが完了した時、一緒に作成したブランチを削除する
- Squash commits when merge request is accepted.
マージリクエストのマージする時、ブランチのコミットを一つにまとめる

マージオプションは後から変更できます。
