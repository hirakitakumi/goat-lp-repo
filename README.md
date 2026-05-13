# GOAT KICKBOXING FES.2 — Sponsorship LP

スポンサー特別プラン提案用 LP（ランディングページ）。

## 概要
- **イベント**: GOAT KICKBOXING FES.2（2026.05.28 / 後楽園ホール）
- **放送**: TV東京系 全国6局ネット
- **特典**: 武尊 引退セレモニー

## 構成
- `index.html` — 単一HTMLファイル（画像はbase64で埋め込み済み）
- 全画像同梱・外部アセット不要
- ファイルサイズ: 約6.8MB

## ローカル確認
```bash
# 単純にブラウザで index.html を開く
# または静的サーバで起動
npx serve .
```

## デプロイ
GitHub Pages で公開可能。Settings → Pages → Source を `main` ブランチに設定。

## カスタマイズ
画像差し替えは HTML 内の `data:image/...;base64,...` を新しいデータURIに置換、
または `embed-images.js` で再ビルド（元画像ファイルが別途必要）。

---

© GOAT Kickboxing Fes. Sponsorship Office
