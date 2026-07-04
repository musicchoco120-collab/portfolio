# AI Build Archive — 開発実績ポートフォリオ

Claude Code の SubAgents / Skills を組み合わせて構築した、SEOブログ自動化の開発記録を紹介するポートフォリオサイトです。

## 公開URL

https://musicchoco120-collab.github.io/claude_test/

## 内容

- 検索意図分析・競合見出し分析・タイトル生成・医療広告ガイドラインチェック・文字数最適化など、実際に検証したSubAgent/Skillsの実行結果スクリーンショットをケーススタディ形式で掲載
- ヒーロー画像はループアニメーション（SVG）で、タイピングする手元と自動化完了の祝祭イラストをクロスフェード表示
- お問い合わせフォーム（フロントエンドのみ、送信処理は未実装）

## ファイル構成

```
portfolio/
├── index.html          # メインページ
├── favicon.svg         # ファビコン
├── README.md           # このファイル
└── assets/
    ├── case-1.png       # file-summarizer検証結果（クロップ）
    ├── case-2.png       # medical-seo-blog-writer検証結果（クロップ）
    ├── case-3.png        # ad-guideline-checker検証結果（クロップ）
    ├── hero-anim-a.svg    # タイピングする手元のループアニメーション
    ├── hero-anim-b.svg    # 自動化完了の祝祭ループアニメーション
    └── og-image.png       # SNSシェア用OGP画像（1200×630）
```

## ローカルでの確認方法

```bash
cd portfolio
python3 -m http.server 8743
# http://localhost:8743 をブラウザで開く
```

## デプロイ

`gh-pages` ブランチのルートに本フォルダの内容を配置し、GitHub Pagesで公開しています。
