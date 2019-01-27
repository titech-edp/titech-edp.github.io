---
layout: page
title: 2018年度「エンジニアリングデザインプロジェクト」最終発表会
---

日頃より東京工業大学CBECプログラムへのご支援を賜り、誠にありがとうございます。

来る平成31年2月9日(土)、同プログラムにて実施しております「エンジニアリングデザインプロジェクト（EDP）」の最終発表会を開催させていただく運びとなり、ご案内申し上げます。

同プロジェクトは、パートナー企業様からお持ち込みいただいたテーマに対し、東工大生、美大生、社会人の受講生がチームを組み、デザイン思考とエンジニアリング思考を活用して解決に取り組む構成となっております。

ご多忙のことと存じますが、ぜひご参加くださいますようご案内申し上げます。

## 開催概要
* 2018年度 東京工業大学エンジニアリングデザインプロジェクト最終発表会
* 会場：[東京工業大学 大岡山キャンパス 西9号館 2階](http://www.dst.titech.ac.jp/outline/facility/image/w9_map.pdf)
* お申込み： <https://titech-edp-2018.peatix.com>

## 当日のスケジュール

1. 受付（12:40-13:00）
   * 会場：デジタル多目的ホール
2. 発表（13:00-15:10）
   * ご挨拶とEDPの紹介［齋藤］
   * パートナー企業によるテーマ紹介（3分）
   * 担当チームによるプレゼンテーション（8分）
   * （全9社9チームが発表します）
   * 途中、適宜休憩を挟みます。
3. デモ展示（15:10-15:50）
   * 会場：コラボレーションルーム
4. 懇親会（16:15-17:45）※参加希望者は、お申し込み時にお知らせください。
   * 会場：コラボレーションルーム
   * 費用：2,000円（EDP受講学生は500〜1,000円を予定）

## パートナー企業とチームの紹介

{% for t in site.data["2018-edp-bc-demoday"] %}
{% if t.desc == "TBD" %}
<div class="panel panel-default">
{% else %}
<div class="panel panel-primary">
{% endif %}
<div class="panel-heading">
{{ t.theme }} by {{ t.company }}
</div>
<div class="list-group">
<a class="list-group-item">
<h4 class="list-group-item-heading">テーマ発表者</h4>
<p class="list-group-item-text">{{ t.presenter }}</p>
</a>
<a class="list-group-item">
<h4 class="list-group-item-heading">担当チーム</h4>
<p class="list-group-item-text">{{ t.team }}</p>
<p class="list-group-item-text">{{ t.desc }}</p>
</a>
</div>
</div>
{% endfor %}

## 本年度のエンジニアリングデザインプロジェクトの様子

以下のURLをご覧ください。

<https://titech-edp.github.io/2018-edp-bc/>

## 書籍のご案内

エンジニアリングデザインプロジェクトの講義内容は書籍『エンジニアのためのデザイン思考入門』（翔泳社）でご確認いただけます。お手にとっていただけますと幸いです。

[![](https://titech-edp.github.io/images/edp-book.png)](http://www.shoeisha.co.jp/book/detail/9784798153858)
