# GitHub Pages セットアップ手順

リポジトリは正常にプッシュされました！
GitHub Pagesを有効化するには、以下の手順に従ってください。

## 📝 設定手順

### 1. GitHubリポジトリにアクセス

以下のURLにアクセスしてください：
```
https://github.com/Privommunity/spa-guide
```

### 2. Settings（設定）を開く

- リポジトリページの右上にある **Settings** タブをクリック

### 3. Pages設定に移動

- 左側のメニューから **Pages** を選択

### 4. ソースブランチを設定

- **Source** セクションで以下を選択：
  - Branch: `main`
  - Folder: `/ (root)`
- **Save** ボタンをクリック

### 5. 公開URLを確認

数分後、ページが公開されます。公開URLは以下のようになります：
```
https://privommunity.github.io/spa-guide/
```

## ✅ 確認事項

設定が完了すると、Pagesセクションの上部に以下のメッセージが表示されます：
```
Your site is live at https://privommunity.github.io/spa-guide/
```

## 📱 SMS送信用URL

入居者にSMSで送信するURLは以下です：
```
https://privommunity.github.io/spa-guide/
```

## 🔄 更新方法

今後、内容を更新する場合は：
1. `index.html` を編集
2. `git add index.html`
3. `git commit -m "更新内容の説明"`
4. `git push origin main`

変更は数分以内にGitHub Pagesに自動反映されます。

## 📞 サポート

何か問題が発生した場合は、GitHub Pagesのドキュメントを参照してください：
https://docs.github.com/ja/pages
