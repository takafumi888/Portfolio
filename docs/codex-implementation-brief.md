# Codex実装指示書

## 目的

既存の静的ポートフォリオリポジトリを、Shopifyエンジニア転職用ポートフォリオサイトに全面リニューアルしてください。

対象リポジトリ：

```bash
https://github.com/takafumi888/Portfolio.git
```

GitHub Pagesで公開できる、HTML/CSS/SCSS/JavaScript構成の静的サイトとして実装してください。

## 重要方針

- Shopify制作会社・EC支援会社の採用担当者に刺さる構成にする
- 派手な演出より、実務理解・設計力・読みやすさを優先する
- 未経験であることは隠さず、Shopify制作フローを理解していることを伝える
- PC/SP対応を必須にする
- 既存の静的サイトをShopify特化ポートフォリオへ置き換える
- デモストア、パスワード、実装内容、設計意図を明確に掲載する

## 実装するページ

```text
index.html
about.html
skills.html
contact.html
works/daily.html
works/eanbe.html
works/sereine.html
docs/portfolio-overview.md
docs/site-map.md
docs/page-section-plan.md
docs/codex-implementation-brief.md
README.md
CASE_STUDY.md
```

## デザイン方針

### 全体
- 落ち着いた実務寄り
- 白、生成り、薄いグレー、チャコールを基調
- Shopifyを想起させるグリーンをアクセントに使用
- 余白を広めに取る
- テキストの可読性を最優先
- 採用担当者が短時間で確認できる情報設計

### 印象
- 誠実
- 実務的
- 清潔感
- EC運用への理解
- 学習の再現性

## 推奨ディレクトリ構成

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
│   └── style.css
├── sass/
│   ├── style.scss
│   ├── _variables.scss
│   ├── _base.scss
│   ├── _layout.scss
│   ├── _components.scss
│   └── _pages.scss
├── js/
│   └── main.js
├── img/
│   ├── works/
│   └── common/
├── docs/
│   ├── portfolio-overview.md
│   ├── site-map.md
│   ├── page-section-plan.md
│   └── codex-implementation-brief.md
├── README.md
└── CASE_STUDY.md
```

## 共通コンポーネント

### Header
- ロゴテキスト：Takafumi Inoue / Shopify Portfolio
- ナビ：Home / Works / About / Skills / Contact / GitHub
- SPではハンバーガーメニュー

### Footer
- 簡単な自己紹介
- GitHubリンク
- Contactリンク
- コピーライト

### Button
- Primary：Worksを見る
- Secondary：GitHubを見る
- Text link：詳細を見る

### Work Card
各作品カードに以下を表示。

- 作品名
- 種別
- 使用テーマ
- 担当範囲
- スキルタグ
- Demo URL
- Password
- 詳細ページリンク

## トップページ要件

### Hero
以下の文言をベースに実装してください。

```text
Shopify Theme Developer Portfolio

Shopifyテーマ実装・ストア設計・運用理解を学習し、実務を想定したECサイト制作に取り組んでいます。
```

CTA：
- Worksを見る
- GitHubを見る

### Selected Works
以下3作品を掲載してください。

#### DAILY石鹸
- 種別：Shopifyスクール課題
- Password：portfolio
- アピール：商品設計、清潔感のあるブランド表現、基本的なテーマカスタマイズ

#### Eanbeデモサイト
- 種別：Shopifyスクール課題
- Password：Eanbe
- アピール：ブランド世界観、コレクション設計、商品導線、ビジュアル設計

#### sereine
- 種別：Shopifyスクール卒業課題
- Password：sereine
- アピール：Riseテーマベース、商品設計、コレクション設計、メタフィールド、Journal、FAQ、商品CSV、実装レポート

### Shopify Focus
以下をカード形式で表示してください。

- Theme Customization
- Store Structure
- Metafields
- Product CSV
- Journal / FAQ
- Documentation

### Skills Preview
Shopify、Frontend、Tools、Documentationの4カテゴリで表示してください。

### Contact CTA
「Shopify制作・EC支援領域での実務に挑戦したいと考えています。」というメッセージを掲載してください。

## Works詳細ページ要件

各Works詳細ページは、以下の構成にしてください。

1. Project Hero
2. Project Summary
3. Shopify Structure
4. Implementation
5. Documentation
6. Challenges & Improvements
7. Screenshots
8. Back to Works

## Works別の内容

### DAILY石鹸

```text
概要：
Shopifyスクール課題として制作した、石鹸ブランドのデモストア。
清潔感・信頼感・商品特徴の伝わりやすさを重視。

担当範囲：
テーマカスタマイズ、商品登録、コレクション設計、基本ページ構成、レスポンシブ確認。

Password：
portfolio
```

### Eanbeデモサイト

```text
概要：
Shopifyスクール課題として制作した、ブランド訴求を重視したデモストア。
商品一覧・商品詳細・ブランド導線の見え方を意識。

担当範囲：
テーマカスタマイズ、商品導線設計、コレクション設計、ビジュアル調整、レスポンシブ確認。

Password：
Eanbe
```

### sereine

```text
概要：
Shopifyスクール卒業課題として制作した、RiseテーマベースのShopifyデモストア。
商品設計、コレクション設計、メタフィールド、Journal、FAQ、商品CSV、実装レポートまで含め、実務に近い制作フローを意識。

担当範囲：
Riseテーマカスタマイズ、商品設計、コレクション設計、メタフィールド設計、Journal作成、FAQ作成、商品CSV作成、実装レポート作成、レスポンシブ確認。

Password：
sereine
```

## Aboutページ要件

以下の要素を含めてください。

- Shopifyエンジニアを目指していること
- 現職で請求事務・物流業務に携わっていること
- 正確性、期限管理、差異確認、継続力を強みとしていること
- EC運用や商品設計への関心
- Shopifyテーマ実装を入口に、ECサイト改善にも関わりたいこと

## Skillsページ要件

以下のカテゴリで整理してください。

### Shopify
- Shopify CLI
- Shopify theme
- Liquid
- sections
- snippets
- schema
- metafields
- product
- collection
- blog / article
- FAQ
- product CSV
- responsive layout

### Frontend
- HTML
- CSS
- SCSS
- JavaScript
- DOM
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

## Contactページ要件

- GitHubリンク
- Emailリンク
- Wantedlyリンク
- Portfolio URL
- 「Shopifyテーマ実装・ECサイト運用改善に関わるポジションに挑戦したい」というメッセージ

## 実装上の注意

- 外部ライブラリは最小限にする
- 画像が未準備の場合はプレースホルダーでよい
- デモストアURLが未確定の場合は `#` とし、コメントで差し替え箇所を明記する
- パスワードは各Worksカードと詳細ページに表示する
- SP表示でカードが1カラムになるようにする
- Lighthouseで極端に低いスコアにならないよう、画像サイズとCSSを意識する
- アクセシビリティとして、alt属性、focus状態、コントラストを考慮する

## 完了条件

- GitHub Pagesで表示できる
- トップページから各Works詳細へ遷移できる
- Works詳細にデモURLとパスワードが掲載されている
- About / Skills / Contactが実装されている
- README.mdとCASE_STUDY.mdが更新されている
- PC/SPで崩れない
