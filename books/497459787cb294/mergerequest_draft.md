---
title: "┗ Draft"
free: false
---

## Draft

Draftとは作業中という意味で、GitLabにおいてはマージリクエストのタイトルに設定する事で、不要なマージを禁止する事ができます。  
イシューからマージリクエスト作成を行なった場合は自動的にDraftが付加されます。

Draftが付いているとマージができませんが、

![](/images/books/497459787cb294/issue_07.png)

Draftを取り除くとマージボタンが有効になります。
(「Mark as ready」ボタンで取り除けます)

![](/images/books/497459787cb294/issue_08.png)


:::message
以前はこの機能を「WIP（Work In Progress）」と呼んでいました。
（"Draft"の部分が"WIP"でした）
WIPはGitHubでも慣例的に使用されていた用語だったためそのまま使用されていたのですが、
色々な職種の人にも広く使ってもらうためには専門用語ではなく一般用語にした方が良いということでGitLabでは変更されました。
:::
