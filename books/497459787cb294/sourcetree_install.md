---
title: "┣ インストール"
free: true
---

## Sourcetreeのインストール

Sourcetreeをインストールして使用できる状態にしましょう。
まずは以下にアクセスします。  
https://ja.atlassian.com/software/sourcetree

そこで「Windows向けダウンロード」からインストーラをダウンロードしましょう。

![](/images/books/497459787cb294/sourcetree_01.png)

### atlassianアカウント作成

インストーラを起動すると以下の様にアカウントの登録を求められますので新規アカウントを作成します。
すでにアカウントを持っている場合は次へ進んでください。

:::message
ここで作成するアカウントとはSourcetree開発元のatlassianのアカウントです。
今回は使用しませんがGitHubやGitLabと同様のBitbucketというリポジトリホスティングサービスも利用できるようになります。
:::

![](/images/books/497459787cb294/sourcetree_02.png)

ブラウザに移動しますのでメールアドレスを入力して「続行」します。

ユーザ名とパスワードの入力を求められます。
(ユーザ名はメールアドレスの@より前を入力しておくと後で混乱しなくなるのでオススメです)
パスワードは任意の文字列でOKです。
botチェックを行った後「Agree and sign up」します。

入力したメールアドレス宛てに認証メールが来ているはずなので、そのメールにあるURLをクリックします。

![](/images/books/497459787cb294/sourcetree_05.png)
![](/images/books/497459787cb294/sourcetree_06.png)

最後にbitbucketの【リモート】リポジトリのアドレスを登録します。
今回はbitbucketは使用しませんがリモートリポジトリとして使用できるようになります。
簡単な質問が出るので任意で回答して完了です。

![](/images/books/497459787cb294/sourcetree_07.png)

### インストール

インストーラに戻って「Bitbucket」を選択します。
アクセス許可を求められますので「アクセスを許可する」を選択します。

![](/images/books/497459787cb294/sourcetree_09.png)
![](/images/books/497459787cb294/sourcetree_10.png)
![](/images/books/497459787cb294/sourcetree_11.png)
![](/images/books/497459787cb294/sourcetree_12.png)

次に必要なモジュールを選択する画面が表示されますので、「Git」と詳細オプションの「改行の自動処理を設定する（推奨）」のみにチェックをつけます。

![](/images/books/497459787cb294/sourcetree_13.png)
![](/images/books/497459787cb294/sourcetree_14.png)
![](/images/books/497459787cb294/sourcetree_15.png)

「この詳細をすべてのリポジトリに使用する」のチェックは外した状態にします。
最後にSSHの読み込み確認ダイアログが表示されますので「いいえ」を選択します。

![](/images/books/497459787cb294/sourcetree_16.png)

![](/images/books/497459787cb294/sourcetree_17.png)
