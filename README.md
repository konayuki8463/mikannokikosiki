# 一般社団法人みかんの木 公式ウェブサイト

千葉・君津のデジタルものづくり拠点「一般社団法人みかんの木」の公式ウェブサイトです。

## 概要

- **コンセプト**: MAKE LOCAL FUN
- **事業内容**: 
  - TukuriE（ツクリエ）- デジタルものづくり拠点
  - Creative Studio - コンテンツ制作
  - Technology Lab - 技術開発・AI活用
  - Workshop - デジタルものづくり体験
  - Community Support - 地域・コミュニティ支援

## 技術スタック

- HTML5
- CSS3 (カスタムCSS)
- Google Fonts (Nunito)
- レスポンシブデザイン

## デプロイメント

このサイトはVercelでホスティングされており、GitHubリポジトリと自動連携しています。

### 自動デプロイメント
- `main`ブランチへのプッシュで自動的にデプロイされます
- プレビューデプロイメントはプルリクエスト作成時に生成されます

## ローカル開発

```bash
# リポジトリをクローン
git clone [リポジトリURL]

# ディレクトリに移動
cd HP

# ローカルサーバーで確認（任意のHTTPサーバーを使用）
python -m http.server 8000
# または
npx serve .
```

## ファイル構造

```
HP/
├── index.html          # メインページ
├── makerspace.html     # TukuriE紹介ページ
├── studio.html         # Creative Studio紹介ページ
├── lab.html           # Technology Lab紹介ページ
├── workshop.html      # Workshop紹介ページ
├── community.html     # Community Support紹介ページ
├── assets/
│   ├── css/
│   │   └── style.css  # メインスタイルシート
│   └── images/        # 画像ファイル
├── tukurie/           # TukuriE関連ページ
└── vercel.json        # Vercel設定ファイル
```

## お問い合わせ

- **メール**: mikannoki.k@gmail.com
- **所在地**: 千葉県君津市市宿375

---

© 2024 一般社団法人みかんの木
