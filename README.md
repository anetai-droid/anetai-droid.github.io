# anetai-droid.github.io

Algo AI の公開サイトを配置する GitHub Pages 用リポジトリです。

中小企業や福祉現場向けの AI 導入支援、AI 開発、業務改善支援に関する静的ページを管理しています。

## 主な内容

- `index.html` - トップページ
- `services.html` - サービス紹介
- `works.html` - 開発実績
- `column.html` / `col-*.html` - コラム記事
- `company.html` - 会社概要
- `contact.html` / `thanks.html` - 問い合わせ関連ページ
- `privacy.html` - プライバシーポリシー
- `assets/`, `images/` - CSS、JavaScript、画像などの静的アセット

## 公開

GitHub Pages で公開する前提の静的サイトです。

HTML/CSS/JS はビルド済みの成果物として配置されています。更新時は、公開 URL・OGP・canonical・sitemap などの整合性も確認してください。

## メモ

- `.nojekyll` を配置しているため、GitHub Pages の Jekyll 処理は無効です。
- `sitemap.xml` と `robots.txt` を含みます。
- 画像やアセットのパスはルート相対パスを前提にしている箇所があります。
