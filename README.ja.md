**目次：**

- [中国語](README.md)
- [英語](README.en.md)
- [日本語](README.ja.md)

# HANDHELD MATRIX V3.0

人気機 8 台の多次元比較ダッシュボード：検索、フィルタ、採点、レーダーチャート比較で、自分に合うゲーム機を選べます。

![HANDHELD MATRIX ダッシュボード](./docs/screenshot.png)

🔗 **オンラインで使用**：[keng0nion.github.io/HANDHELD-MATRIX-V3.0](https://keng0nion.github.io/HANDHELD-MATRIX-V3.0/)

---

## 機能

- **デバイスカード**：8 台の価格・バッテリー・重量・画面・ハードウェアスペックを一覧表示、性能／バッテリー／画面の 3 軸スコアバー付き
- **MATRIX セレクター**：名前／ブランド／別名／CPU のあいまい検索（Fuse.js）、価格と重量のダブルスライダーフィルタ、ワンクリックプリセット（性能狂、純家庭用機、OLED ONLY、120Hz+、<500g、<¥1500）
- **MATRIX COMPARE**：複数台にチェックして比較パネルへ。レーダーチャート（Chart.js）＋スペック比較表＋TOGGLE DIFF 差分ハイライト
- **ポスター書き出し**：html2canvas で現在のビューをワンクリックで画像に書き出し
- **ダーク／ライトテーマ切替**、HUD 時計とシステムステータスの装飾

---

## 収録デバイス

| デバイス | ブランド | カテゴリ | 価格 |
|---|---|---|---|
| Steam Deck OLED | Valve | PC ゲーム機 | ¥4,200 |
| ROG Ally X | ASUS | PC ゲーム機 | ¥5,800 |
| Legion Go 2 | Lenovo | PC ゲーム機 | ¥5,800 |
| AYANEO 2S | AYANEO | PC ゲーム機 | ¥5,500 |
| GPD WIN 4 (2025) | GPD | PC ゲーム機 | ¥5,300 |
| Switch OLED | Nintendo | 家庭用ゲーム機 | ¥2,200 |
| Miyoo Mini Plus | Miyoo | レトロゲーム機 | ¥400 |
| Retroid Pocket 4 Pro | Retroid | レトロゲーム機 | ¥1,300 |

価格とスペックは `devices.json` のデータに準拠（人民元建て）。

---

## ローカルで実行

純静的なシングルページ：clone 後に `index.html` をダブルクリックで開くだけ、または任意の静的サーバーでディレクトリ全体をホスト。

- `index.html` — ページと全ロジック
- `devices.json` — ゲーム機スペックデータ

外部 CDN 依存（Fuse.js、Chart.js、nouislider、html2canvas、Lucide、vanilla-tilt）。初回オープン時はネット接続が必要。

---

## License

[MIT](./LICENSE)
