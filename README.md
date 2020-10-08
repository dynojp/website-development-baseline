# ウェブサイト制作ベースライン

## HTML コーディング

- [ ] HTML5 を使う
- [ ] `<main>` `<article>` `<time>` 等のセマンティックタグを使う

## CSS コーディング

- [ ] CSS3 を使う
- [ ] HTML 内でのインラインスタイル（ `style` 属性）は使わない
- [ ] SCSS 等の AltCSS を使う

## `<head>` タグ

- [ ] meta charset タグを含める
- [ ] title タグを含める
- [ ] link favicon タグを含める
- [ ] link apple-touch-icon タグを含める
- [ ] meta description タグを含める
- [ ] meta theme_color タグを含める
- [ ] meta manifest タグを含める
- [ ] OGP （ Open Graph Protocol ）タグを含める

## SEO

- [ ] Lighthouse スコアを見る
- [ ] Core Web Vitals スコアを見る
- [ ] Search Console の警告に対応する
- [ ] マシン向けサイトマップを設置する
- [ ] `robots.txt` を設置する

## デザイン

- [ ] レスポンシブ対応を行う
- [ ] アクセス実績に応じて端末の優先度を決める
- [ ] テーマの画像は倍精度のものを用意する

## セキュリティ

- [ ] 利用ライブラリのセキュリティ情報をウォッチし速やかに対応する
- [ ] HTTPS 化（ SSL 対応）を行う
- [ ] 管理画面のログインフォームに reCAPTCHA を付ける
- [ ] サイト全体のバックアップを定期的にとる
- [ ] CMS / フレームワークの API を適切に使って各種インジェクション対策を行う

## セキュリティ（ WordPress ）

- [ ] コアとプラグインの自動アップデート機能を利用する
- [ ] セキュリティプラグインを導入する

## パフォーマンス

- [ ] link prefetch preload タグを使う
- [ ] CSS は `<head>` の末尾で、 JavaScript は `<body>` の末尾で読み込む
- [ ] 非同期読み込みを使う
- [ ] Lighthouse スコアを見る
- [ ] Core Web Vitals スコアを見る
- [ ] 匿名ユーザー向けのページをキャッシュする

## SNS

- [ ] 主要な SNS のタイムラインを設置する
- [ ] シェアボタンを設置する

## 解析

- [ ] Google Analytics または Google Tag Manager を導入する

## サポートブラウザ

- [ ] サポート対象: Chrome / Edge / Firefox / Safari
- [ ] サポート対象外: 旧 Android ブラウザ / Internet Explorer 11

## 開発

- [ ] Git でコードを管理する
- [ ] パッチ適用が必要な場合はパッチファイルも Git で管理する
- [ ] チケットでタスクを管理する
