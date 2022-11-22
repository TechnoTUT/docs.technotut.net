# 概要
ここではこのドキュメントとTechnoTUTホームページの編集方法について説明します。

## 構成
このドキュメントとTechnoTUTホームページはGitHubとCloudflare Pagesで構成されています。
Cloudflare Pagesは、GitHubと連携して、GitHub上のリポジトリを自動でデプロイすることができます。  
ですから、内容を書き換えるには、GitHub上のリポジトリを編集する必要があります。

## 手順
全体の手順は以下の通りです。  
1. このドキュメントのソースをcloneまたはpullします。
2. 作業用のブランチを作成します。
3. 作業用のブランチでドキュメントを編集します。
4. 編集が完了したらpushします。
5. GitHub上でプルリクエストを作成します。
6. 管理者によってプルリクエストが承認されたら、自動でデプロイされます。