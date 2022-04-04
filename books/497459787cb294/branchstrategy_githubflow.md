---
title: "┣ GitHub-flow"
free: false
---

## GitHub-flow

![](/images/books/497459787cb294/githubflow.png)
*https://docs.github.com/ja/get-started/quickstart/github-flow*

### 特徴

Git-flowをよりシンプルにしたのがGitHub-flowです。GitHub-flowではfeatureブランチとmasterブランチしか使いません。シンプルでわかりやすいフローで、多くの開発チームが採用し成功を収めています。

全てをmasterブランチにマージし、こまめにデプロイすることで、デプロイ待ちのコードの量を最小限にできます。

### メリット

小さい規模から大規模まで対応できます。  
ほぼ全フローの中で最速の超高速リリースが可能です。これはSaaS（webサービス）のような常に機能アップし続けるようなプロジェクトに最適です。  
コードを修正してから適用までが早いためコンフリクト（修正箇所の衝突）が少なくなるので管理者の負担が比較的少ないです。  
非常にシンプルなため多くの開発で採用しやすい簡単、明瞭なフローです。また、Gitでの開発初心者やノンプログラマでも理解しやすいです。

### デメリット

権限はmasterへのコミット権限(コミッタ)と パッチ作成者(コントリビュータ)しかないため、組織体制によっては適用できない可能性があります。  
このフロー自体にはリリース管理機能(アプリのバージョンetc)が無いので、別途規約を用意する必要があります。
またテスト環境、本番環境などの環境分けを行う仕組みもありません。

### 使用方法

#### ①featureブランチの作成

イシューが発行されてその課題に対応するための開発をmasterブランチから切ったfeatureブランチを作成します。

#### ②featureブランチのマージ

マージリクエストを使用してfeatureブランチで修正した内容をレビューした後、問題なければmasterブランチにマージします。（マージ後はfeatureブランチを削除します）

#### ③リリース

masterブランチからリリースタイミングでtagを設定します。