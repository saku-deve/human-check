# 人間チェック

「自分は人間かな？」と思ったときに、気軽にチェックできる小さな静的ウェブサイトです。

**これはジョーク・自己申告用のサイトです。本人確認やボット検出などのセキュリティ機能はありません。**

## デモ・公開方法

このリポジトリはHTML/CSS/JavaScriptだけで動作します。Node.js、ビルドツール、環境変数、APIキーは必要ありません。

### GitHub Pagesで公開

1. このリポジトリのファイルをGitHubにアップロードします。
2. GitHubリポジトリの **Settings → Pages** を開きます。
3. **Build and deployment** の **Source** を `Deploy from a branch` にします。
4. Branchを `main`、フォルダーを `/ (root)` にして保存します。
5. 公開URLが表示されるまで待ちます。

### Netlifyで公開

1. Netlifyで **Add new site → Import an existing project** を選び、GitHubリポジトリを接続します。
2. Build commandは空欄、Publish directoryは `.`（ドット）にします。
3. Deployします。

GitHubからZIPを直接アップロードする場合は、ZIPを解凍し、**このフォルダーの中身**をリポジトリのルートにアップロードしてください。ZIPファイルそのものをリポジトリに置く必要はありません。

## ファイル構成

```text
.
├── LICENSE
├── README.md
└── index.html
```

## 技術構成

- HTML5
- CSS
- Vanilla JavaScript
- 外部ライブラリ・外部APIなし

## プライバシー

入力内容やチェック状態を外部サーバーへ送信する処理、CookieやLocal Storageへの保存処理はありません。ただし、公開先のホスティングサービスは通常のアクセスログ等を取得する場合があります。ホスティングサービス側のプライバシーポリシーも確認してください。

## ライセンス

MIT License。詳細は [LICENSE](LICENSE) を確認してください。
