---
title: "┗ GitLabと連携"
free: true
---

## Sourcetree+GitLab連携

SourcetreeからGitLab内のリポジトリを参照できる様に設定します。
「ツール」→「オプション」からオプション画面を表示し、
認証タブへ移動します。

タブのアカウントから「追加」を選択しますが、画面が表示されたらそのままにします。

![](/images/books/497459787cb294/sourcetree_18.png)
![](/images/books/497459787cb294/sourcetree_19.png)

GitLabに戻って、右上のアイコンから「設定」を選択します。

![](/images/books/497459787cb294/sourcetree_24.png)

ユーザ設定画面の「アクセストークン」を選択します。
名前に「Sourcetree」と入力して、Scopesから「api」をチェックしたら、
「Create personal access token」でアクセストークンを作成します。
※表示されたトークンはこの画面を離れると２度と参照できなくなりますので画面を閉じない様にしてください。

![](/images/books/497459787cb294/sourcetree_20.png)
![](/images/books/497459787cb294/sourcetree_25.png)

Sourcetreeに戻ってHost欄を以下の画像の通り設定後、
「Personal Access Token を再読み込み」を選択します。

### GitLab CE版（自前で管理）を使用している場合

ホストURLにサーバーのURLを設定してください。
![](/images/books/497459787cb294/sourcetree_21.png)

### GitLab.com（SaaS）を使用している場合

ホストURLの入力は不要です。
![](/images/books/497459787cb294/sourcetree_27.png)

ユーザ名はメールアドレスを入力し、パスワードに先ほど作成したアクセストークンを設定します。

![](/images/books/497459787cb294/sourcetree_22.png)
![](/images/books/497459787cb294/sourcetree_23.png)

間違いがなければ認証に成功します。
これで完了です。

Remoteを選択すると、追加したGitLabアカウントが表示されているはずですので、それを選択すると、リポジトリ一覧が表示される様になります。

![](/images/books/497459787cb294/sourcetree_26.png)
