---
layout: page
title: エンジニアリングデザイン研究会（SIGED）
---

東京工業大学CBECプログラムでは、学生向けの講義に社会人の方々にも参加していただくことで、あらゆる境界を超えてチームとして世の中に新しい価値を生む力を育成し、その価値を実現する機会を持続的に提供することを目指しています。

本「エンジニアリングデザイン研究会（SIGED）」は、CBECプログラムの一部である「エンジニアリングデザインプロジェクト（EDP）」で得られた知見を共有・発展させ、企業のみなさまや社会に還元することを目的に発足いたしました。

## 開催情報

<ul>
{% assign sorted = site.pages | sort: 'title' %}
{% for p in sorted %}
  {% if p.category == "siged" %}
<li><a href="{{p.url}}">{{ p.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>


