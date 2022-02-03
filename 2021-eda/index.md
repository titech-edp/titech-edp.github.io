---
layout: page
title: 2021年度「エンジニアリングデザイン応用」
tags: [lecture]
---

# Syllabus

[2021  Engineering Design Advanced - TOKYO TECH OCW](http://www.ocw.titech.ac.jp/index.php?module=General&action=T0300&GakubuCD=2&GakkaCD=321502&KeiCD=15&course=2&KamokuCD=321502&KougiCD=202028119&Nendo=2020&vid=03&lang=EN)

# Teaching Assistants

* Motoki MORITANI
* Rin ITO
* Yuta SUKA
* Y. Okamoto
* Mayu Narukawa
* かしまりかこ

# Venue

東京工業大学 大岡山キャンパス 石川台3号館2階 統合創造工房（<https://www.titech.ac.jp/maps/ookayama/>）

## 以下の場合来校しないでください

1. 体温が,37.5°C以上ある場合
2. 体温に関わらず,風邪の諸症状がある場合
3. PCR 検査等を受けるまたは検査結果を待っている場合(自覚症状等により感染が強く疑われるまたは濃厚接触者と判断された)
4. 新型コロナウイルス接触確認アプリ(COCOA)等により濃厚接触の疑いがあると判断された場合
    * 『検査を要する』と判断された場合検査を要さないと判断された場合は登校可能。
    *  ただし,学生は,14 日間は自身で経過観察を行うためその期間に体調の変化があった場合には, (2)の取扱いとなることがある
5. 新型コロナウイルス感染症に罹患した場合(無症状〜重症問わず)
    * 同居家族がPCR検査結果を待っている場合は相談してください

* Zoomで参加してもらえば,出席扱いにします.(グループワークにも参加できます)
* Zoom参加が厳しい場合は相談してください

以上の場合以外でも,気軽に・事前に相談してください!

# Schedule

[![Image from Gyazo](https://i.gyazo.com/c6a78bc95a305cb663626351885b5df1.png)](https://gyazo.com/c6a78bc95a305cb663626351885b5df1)

## 6/19

[![Image from Gyazo](https://i.gyazo.com/dd307b8d9511e5e27bf972400ca67e94.png)](https://gyazo.com/dd307b8d9511e5e27bf972400ca67e94)

## 7/03

* [見えないものはないのと同じ](https://medium.com/titech-eng-and-design/%E8%A6%8B%E3%81%88%E3%81%AA%E3%81%84%E3%82%82%E3%81%AE%E3%81%AF%E3%81%AA%E3%81%84%E3%81%AE%E3%81%A8%E5%90%8C%E3%81%98-2566cc5a7c54)

## 7/10

[![Image from Gyazo](https://i.gyazo.com/0ba09aecad419a1d3af66316dd731b27.png)](https://gyazo.com/0ba09aecad419a1d3af66316dd731b27)

## 7/31

* Presentation
  * Product Pitch / 5min.
  * Design Process / 5min.
* Lightning Talks (自己紹介）

# Design Prompt (Theme)

* 共働き夫婦の在宅勤務時の昼食体験をデザインせよ
* Design a lunch experience for dual-earner couples working from home.



# Presentation Slides

{% for d in site.data["2021-eda"] %}
## {{ d.name }}

<iframe src="{{ d.url }}/embed?start=false&loop=false&delayms=3000" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<iframe width="560" height="315" src="https://www.youtube.com/embed/{{ d.movie }}" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{% endfor %}
