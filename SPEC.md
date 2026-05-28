# 副業税金計算【無料】確定申告いくら？副業収入・所得税シミュレーター - 技術仕様書

## 概要

**サービス名**: Sidejob Tax Simulator
**バージョン**: 1.1.0
**更新日**: 2026-05-28

## 変更履歴

### v1.1.0 (2026-05-28)
- PWA theme-color を全5ページで #6366f1（インディゴ）→ #16a34a（グリーン）に修正
- page-loader-sj の spinner 色をブランドカラーに統一
- OGP画像参照を ogp-default.png → sidejob-tax-simulator/ogp.png に変更
- social-proof セクションのTailwindクラスをインラインスタイルに変換
- 末尾の大量重複コメントを削除（ファイルサイズ削減）
- フッター著作権年を 2025 → 2025-2026 に修正
**URL**: https://appadaycreator.com/sidejob-tax-simulator/

副業収入・経費を入力して確定申告の所得税・住民税を無料計算。20万円ルールの判定も対応。

## データ管理

- **ストレージ**: ブラウザ localStorage（外部API通信なし）
- **永続化**: ページ読み込み時に自動復元
- **クリア**: ブラウザのサイトデータ削除で初期化

## 技術スタック

- HTML5 / CSS3 / Vanilla JavaScript
- PWA対応（manifest.json / Service Worker）
- レスポンシブデザイン（モバイルファースト）

## 使い方

1. ページを開き、入力フォームの項目を確認する
2. 必要な情報を入力または選択する
3. 実行ボタンをクリックして結果を取得する
4. 表示された結果・アドバイスを確認する
5. 必要に応じてコピー・SNSシェアで活用する

## よくある質問（FAQ）

**Q: 副業税金計算は無料で使えますか？**

はい、完全無料・登録不要でご利用いただけます。

**Q: 何回でも使えますか？**

はい、回数制限なく何度でもご利用いただけます。

**Q: 入力したデータはサーバーに送信されますか？**

いいえ。すべての処理はブラウザ内で完結し、入力内容はサーバーへ送信されません。

**Q: スマートフォンでも使えますか？**

はい、スマートフォン・タブレット・PCすべてに最適化されています。

**Q: 結果を保存・共有できますか？**

スクリーンショットでの保存またはSNSシェアボタンからご共有いただけます。


## 関連サービス

- [睡眠の質チェッカー](https://appadaycreator.com/sleep-quality-checker/)
- [BMI・体重管理](https://appadaycreator.com/bmi-body-tracker/)
- [家計簿診断](https://appadaycreator.com/household-budget-analyzer/)

## テスト

| ファイル | フレームワーク | 概要 |
|---------|--------------|------|
| `tests/e2e/` | Playwright | 本番URL対象E2E（Jest対象外） |

## デプロイ

GitHub Pages（mainブランチ push → 自動デプロイ）

## ライセンス

MIT License
