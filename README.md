# Shopify Theme Developer Portfolio

Shopifyエンジニア転職を目的とした、井上孝文のポートフォリオサイトです。

GitHub Pagesで公開できる静的HTML/CSS/JavaScript構成で、Shopifyテーマ実装だけでなく、商品設計、コレクション設計、メタフィールド、Journal、FAQ、商品CSV、実装レポートなど、ECサイト制作・運用に関わる要素を整理して掲載しています。

## Demo

```text
https://takafumi888.github.io/Portfolio/
```

## Concept

**Shopifyテーマ実装・ストア設計・運用理解まで見せる、実務寄りのECポートフォリオ**

未経験からShopifyエンジニアを目指すにあたり、単なるWeb制作作品集ではなく、Shopify制作会社・EC支援会社の現場を意識したポートフォリオとして制作しています。

## Pages

```text
/
├── index.html
├── about.html
├── skills.html
├── contact.html
├── works/
│   ├── daily.html
│   ├── eanbe.html
│   └── sereine.html
├── css/
├── sass/
├── js/
├── img/
├── docs/
├── README.md
└── CASE_STUDY.md
```

## Works

### DAILY石鹸

- 種別：Shopifyスクール課題
- Demo URL：https://dailyadvance-designcomp.myshopify.com/
- Password：`portfolio`
- 取り組んだこと：テーマカスタマイズ、商品登録、コレクション設計、基本ページ構成、レスポンシブ確認
- アピール：商品設計、清潔感のあるブランド表現、基本的なテーマカスタマイズ

### Eanbeデモサイト

- 種別：Shopifyスクール課題
- Demo URL：https://tredify-demostore.myshopify.com/
- Password：`Eanbe`
- 取り組んだこと：テーマカスタマイズ、商品導線設計、コレクション設計、ビジュアル調整、レスポンシブ確認
- アピール：ブランド世界観、コレクション設計、商品導線、ビジュアル設計

### sereine

- 種別：Shopifyスクール卒業課題
- Demo URL：https://fleur-sereine-graduate.myshopify.com/
- Password：`sereine`
- 使用テーマ：Shopify公式テーマ Rise
- 取り組んだこと：Riseテーマカスタマイズ、商品設計、コレクション設計、メタフィールド設計、Journal作成、FAQ作成、商品CSV作成、実装レポート作成、レスポンシブ確認
- アピール：実務に近い制作フロー、ストア設計、運用理解、ドキュメント化

## Skills

### Shopify

- Shopify CLI
- Shopify theme
- Liquid
- sections / snippets
- schema / settings
- metafields
- product / collection
- blog / article
- FAQ
- product CSV
- responsive layout

### Frontend

- HTML
- CSS
- SCSS
- JavaScript
- DOM操作
- responsive design

### Tools

- Git
- GitHub
- VSCode
- Shopify CLI
- Chrome DevTools
- Codex

### Documentation

- README
- CASE_STUDY
- 実装レポート
- 設計メモ

## Implementation Notes

- GitHub Pagesでそのまま公開できる相対パス構成
- PC/SP対応
- SPではハンバーガーメニューを使用
- 各Works詳細ページに概要、担当範囲、Shopify設計、実装内容、パスワードを掲載
- 採用担当者が短時間で確認できるよう、作品情報と連絡導線を整理

## Development

静的サイトのため、ブラウザで `index.html` を直接開いて確認できます。ローカルサーバーで確認する場合は以下のように起動します。

```bash
python3 -m http.server 8000
```

## Goal

Shopify制作会社・EC支援会社・Web制作会社の採用担当者に対して、以下を伝えることを目的としています。

- Shopifyテーマ実装の基礎を理解している
- 商品・コレクション・メタフィールドなど、ストア設計を意識できる
- EC運用を想定してFAQ、Journal、商品CSVを扱える
- 実装内容をドキュメント化できる
- 未経験からでも現場に入るための基礎体力がある
