# My Portfolio

ポートフォリオサイトとAI×Webサービス開発企業HP

## デプロイ方法

### GitHub Pages へのデプロイ

このリポジトリは GitHub Pages でホストできます。以下の手順でデプロイしてください：

#### 方法1: GitHub Actions を使用（推奨）

1. リポジトリの **Settings** > **Pages** に移動
2. **Source** で **GitHub Actions** を選択
3. 以下のコマンドで変更をプッシュ：

```bash
git add .
git commit -m "Setup GitHub Pages deployment"
git push origin master
```

4. GitHub Actions が自動的にデプロイを実行します
5. 数分後、`https://rock-hill.github.io/my-portfolio/` でサイトにアクセスできます

#### 方法2: シンプルな方法

1. リポジトリの **Settings** > **Pages** に移動
2. **Source** で **Deploy from a branch** を選択
3. **Branch** で `master` を選択
4. **Folder** で `/ (root)` を選択
5. **Save** をクリック

## ファイル構成

```
my-portfolio/
├── index.html          # ポートフォリオサイト
├── style.css          # スタイルシート
├── script.js          # JavaScript
├── hp/
│   └── index.html     # AI×Webサービス開発企業HP
└── .github/
    └── workflows/
        └── deploy.yml # GitHub Actions ワークフロー
```

## アクセスURL

- ポートフォリオサイト: `https://rock-hill.github.io/my-portfolio/`
- 企業HP: `https://rock-hill.github.io/my-portfolio/hp/`

## 注意事項

- GitHub Pages は静的サイトのみをホストできます
- サーバーサイドの処理が必要な場合は、別のホスティングサービスを使用してください
