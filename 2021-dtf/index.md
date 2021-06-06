---
layout: page
title: 2021 デザイン思考基礎
tags: [lecture]
---

# スケジュール

[![Image from Gyazo](https://i.gyazo.com/327844f8c925bc229a42df256230234b.png)](https://gyazo.com/327844f8c925bc229a42df256230234b)

# テーマ

Design an experience that makes people get friendly without eating and/or drinking together.

一緒に飲み食いしなくても仲良くなれる体験をデザインせよ。

# スライド

{% for d in site.data["2021-dtf"] %}
## {{ d.name }}

<iframe src="{{ d.url }}/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

{% endfor %}

