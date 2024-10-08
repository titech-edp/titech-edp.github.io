---
layout: page
title: 2017年度「デザイン思考基礎b」
tags: [lecture]
---

# シラバス

[デザイン思考基礎 B - TOKYO TECH OCW](http://www.ocw.titech.ac.jp/index.php?module=General&action=T0300&GakubuCD=2&GakkaCD=321502&KeiCD=15&course=2&KamokuCD=321502&KougiCD=201713496&Nendo=2017&vid=03)

# テーマ

［対象ユーザー］のためのイノベーティブな［春のイベント］体験をデザインせよ。

1. 大学生 / 卒業旅行
2. 社会人 / 花見
3. 新しくやってきた人 / 歓迎会

（1〜3から好きなものをチームで選んでください）

# 最終レポート

{% for t in site.data["2017-dtf-b-teams"] %}
<h2>{{ t.name }}</h2>
<blockquote>デザインプロンプト: {{ t.theme }}</blockquote>
<div class="btn-group" role="group">
  {% for d in t.data %}
    <a href="{{ d[1] }}" role="button" class="btn"><i class="fas fa-arrow-circle-right"></i>{{ d[0] }}</a>
  {% endfor %}
</div>
{% endfor %}


# 日程

## [DTFb-1] 4/8（土）10:00-15:50

- ガイダンス
- モジュール１：デザイン思考への導入
- チームビルディング
- モジュール２：調査と気づき
- ふりかえり

### 宿題：

- ユーザーリサーチ（インタビューと文字起こし）：2人以上
- 観察（写真撮影と説明）：1箇所以上
- アナロガスインスピレーション：1つ以上

上記をまとめてPDFにして、リンク（Google DriveやDropboxなどのURL）を``Slack#homework-20170408``に投稿すること。

## [DTFb-2] 4/22（土）10:00-15:50

- モジュール３：統合と機会領域
- モジュール４：アイデア創造とコンセプト開発
- ふりかえり

### 宿題：

- チームメンバーのレポートを読んで、さらにリサーチを続ける
- POVを新たに1つ以上作成する
- HMWを新たに1つ以上作成する
- 4コマ漫画（コンセプト）を新たに1つ以上作成する

上記をまとめてPDFにして、リンク（Google DriveやDropboxなどのURL）を``Slack#homework-20170422``に投稿すること。

- Slackでチームの議論を続けること
- 次回のプロトタイピングに必要なツールや材料を持参すること

## [DTFb-3] 5/13（土）10:00-15:50

- モジュール５：プロトタイピング
- プロトタイプ制作

### 宿題：

- 新しいPOVとHMWを作成する
- コンセプトスケッチを描く
- 作成したプロトタイプの写真を撮影する

上記をまとめてPDFにして、リンク（Google DriveやDropboxなどのURL）を``Slack#homework-20170513``に投稿すること。

- Slackでチームの議論を続けること
- 次回のプロトタイピングに必要なツールや材料を持参すること

## [DTFb-4] 6/3（土）10:00-15:50

- モジュール６：ビジネスデザイン
- モジュール７：ストーリーテリング
- プロトタイプ制作 + 発表の準備

### 宿題：

- 発表の準備

## [DTFb-5] 6/10（土）10:00-15:50

- 発表の準備
- モジュール８：最終発表（各チーム10分ずつ）
  1. エレベーターピッチ
  2. プロトタイプを使用した寸劇
  3. デザインプロセスの説明

### 宿題：

- 個人レポート：Google Formから提出
- チームレポート：こちらで用意したWordのテンプレートを使い、PDFに変換して、リンク（Google DriveやDropboxなどのURL）を``Slack#homework-20170603``に投稿すること。

# その他の情報源

- Slack: [https://cbec-dtf-2017.slack.com](https://cbec-dtf-2017.slack.com)
