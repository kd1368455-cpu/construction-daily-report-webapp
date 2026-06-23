# 作業日報入力システム（Construction Daily Report Web App）

このアプリは、建設現場で使用される「作業日報」を想定して作成した  
**HTML・CSS・JavaScript製の Web アプリケーション**です。

バックエンドは不要で、入力したデータはすべてブラウザの  
`localStorage` に保存されます。  
ポートフォリオとして、業務システム風のUI・入力フォーム・一覧表示などを再現しています。

---

## ■ 主な機能

- 日報の入力  
  - 日付  
  - 現場名  
  - 作業内容  
  - 作業時間（時間数）  
  - 進捗率（スライダー）

- 日報データの保存（localStorage）
- 日報一覧の表示（テーブル形式）
- 個別削除
- 全件削除
- 入力フォームのクリア

---

## ■ 使用技術

- **HTML5**
- **CSS3**
- **JavaScript（Vanilla JS）**
- **localStorage（ブラウザ保存）**

---

## ■ 使い方

1. 本リポジトリをクローンします。
git clone https://github.com/your-account/construction-daily-report-webapp.git (github.com in Bing)

2. `index.html` をブラウザで開くだけで動作します。  
   サーバーやビルド工程は不要です。

---

## ■ フォルダ構成

.
├─ index.html
└─ README.md

---

## ■ 注意事項

- 本アプリは学習・ポートフォリオ用に作成した簡易システムです。
- データはブラウザの `localStorage` に保存されるため、  
  ブラウザのデータを削除すると日報も消えます。
