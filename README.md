# Forensic-Sign
著作権を守るサインを作品にスタンプします。

## GitHub Pages公開手順

1. GitHubリポジトリの **Settings > Pages** を開く
2. **Build and deployment** の **Source** を **GitHub Actions** に変更する
3. `main` ブランチに push すると、`Deploy static content to Pages` ワークフローが実行される
4. 公開URL（例）：`https://abeyuuki-hue.github.io/Forensic-Sign/`

## Google サイト（Google Sites）埋め込み用ページ

Google サイトなどの iframe 埋め込み環境では、ブラウザのセキュリティ制限（Sandbox 属性）により、「💾 ほぞんする」ボタンからの直接ダウンロードがブロックされます。

そのため、Google サイトへの埋め込み専用として、保存時にポップアップ（長押し・右クリック保存を案内するモーダル）を表示する専用ページ `google-sites.html` を用意しています。

- **埋め込み用URL**: `https://abeyuuki-hue.github.io/Forensic-Sign/google-sites.html`
- **埋め込み手順**:
  1. Google サイトの編集画面で **「埋め込み」** を選択
  2. **「URL」** タブに上記の埋め込み用URLを入力
  3. 配置した埋め込みエリアのサイズをお好みに調整してください。

