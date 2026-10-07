# MONO

白黒を基調にした、1ページ完結のシンプルなTodo・ルーティーントラッカーです。

## 機能

- TODAY / NEXT 7 DAYS / LATER のタスク管理（明日から7日後までがNEXT 7 DAYS。8日後以降と期限なしはLATER）
- グループ別の色付きマーカーと、GROUPSからの色変更
- 四角いチェックボタンで即時完了
- 完了タスクをHANGARに3日間保持
- HANGARから未完了へ復帰
- タスクごとのメモ保存とホバー表示
- ルーティーンの追加・編集・削除
- 7日間のルーティーン履歴
- 移動できるタスク追加・メモ編集ウィンドウ

## 使い方

公開版は [MONO](https://goldfishstar0055.github.io/Chatgpt/) から使用できます。`index.html`を直接ブラウザで開くこともできます。外部ライブラリを読み込まない単一HTMLです。タスク、ルーティーン、グループの色はそのブラウザのローカルストレージに保存され、端末間では同期されません。

## GitHub Pages

`main`への更新は `.github/workflows/pages.yml` により自動でデプロイされます。PagesのSourceは **GitHub Actions** に設定されています。
