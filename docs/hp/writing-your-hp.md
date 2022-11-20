# ドキュメントの書き方
## 概要
ここではTechnoTUTホームページの書き方について説明します。  
また、TechnoTUTホームページについても同様の手順で書くことができます。  
このドキュメントの書き方については[こちら](write-your-docs.md)をご覧ください。

## 手順
1. このドキュメントのソースをcloneまたはpullします。
2. 作業用のブランチを作成します。
3. 作業用のブランチでドキュメントを編集します。
4. 編集が完了したらpushします。
5. GitHub上でプルリクエストを作成します。
6. 管理者によってプルリクエストが承認されたら、自動でデプロイされます。

### プルリクエストについて
[こちら](https://backlog.com/ja/git-tutorial/pull-request/01/)をご覧ください。

### 書式
TechnoTUTホームページはHugoを利用しています。HugoではMarkdown形式でページを書きます。   
Markdownの書式については[こちら](https://www.markdown.jp/what-is-markdown/)を参照してください。  
DiscordやSlackなどのチャットツールで使われていることが多いので、既に使っている人はすぐに使えると思います。

### 編集
contentフォルダ内のファイルを操作します。  
例えば、Blogページ内に新たにページを作成する場合は、`/content/blog`内に任意の名前で`.md`ファイルを作成し編集します。  

### プレビュー
#### Hugoのインストール
Hugoをインストールします。  
[こちら](https://gohugo.io/getting-started/installing/)を参照してください。
#### プレビューの実行
`hugo -D server`を実行します。  
任意のブラウザで`http://localhost:1313/`にアクセスするとプレビューが表示されます。