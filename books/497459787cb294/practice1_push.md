---
title: "┣ push(プッシュ)"
free: false
---

## push(プッシュ)

最後にpush(プッシュ)を行います。  
プッシュとは、【ローカル】リポジトリの変更内容を【リモート】リポジトリに反映する作業を指します。これを行うことで初めて他の人が変更内容を確認することができる様になります。

タブ上部の「プッシュ」を押下すると以下のダイアログが表示されます。  

![](/images/books/497459787cb294/practice_16.png)

プッシュはブランチ単位で行うことができます。  
今回は新しく作成したブランチをプッシュしたいので、そのブランチだけチェックを付けます。チェックをつける前は「リモートブランチ」が空欄となっています。これは、まだ【リモート】リポジトリ上には【ローカル】リポジトリで作成したブランチが無いためです。  
Sourcetreeはブランチを自動的に作成もしてくれるのでチェックを付けるだけで同名のブランチを【リモート】リポジトリに作成してくれます。  
「プッシュ」を押下すれば完了です。

![](/images/books/497459787cb294/practice_07.png)

プッシュが完了すると、左側にあるリモートにブランチが追加されています。  

![](/images/books/497459787cb294/practice_08.png)

またGitLabにも追加されているので確認してみてください。（ブランチ・タグの切り替えプルダウンで確認できます）

![](/images/books/497459787cb294/practice_09.png)