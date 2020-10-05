---
layout: page
title: 教員チームの紹介
---

<div class="row">

{% for f in site.data["faculty"] %}
  <div class="col-sm-4 align-self-stretch">
<div class="card h-100">
  <div class="card-body">
  <h2>{{ f.name }}</h2>
  <p>{% for t in f.title %}<span style="font-size: 0.8em;"><em>{{t}}</em></span><br />{% endfor %}</p>
  <img src="/images/faculty/{{ f.photo }}" alt="{{ f.name }}" class="media-object rounded-circle">
  <p style="font-size: 0.9em;">{{ f.profile }}</p>
  {% if f.url != "" %}
  <p><a href="{{ f.url }}"><i class="fas fa-home"></i></a></p>
  {% endif %}
  </div>
</div>
</div>
{% endfor %}

</div>

## 特任・非常勤

<div class="row">

{% for f in site.data["faculty-sa"] %}
  <div class="col-sm-4 align-self-stretch">
<div class="card h-100">
  <div class="card-body">
  <h2>{{ f.name }}</h2>
  <p>{% for t in f.title %}<span style="font-size: 0.8em;"><em>{{t}}</em></span><br />{% endfor %}</p>
  <img src="/images/faculty/{{ f.photo }}" alt="{{ f.name }}" class="media-object rounded-circle">
  <p style="font-size: 0.9em;">{{ f.profile }}</p>
  {% if f.url != "" %}
  <p><a href="{{ f.url }}"><i class="fas fa-home"></i></a></p>
  {% endif %}
  </div>
</div>
</div>
{% endfor %}

</div>

## サポート教員

<div class="row">

{% for f in site.data["faculty-supporters"] %}
  <div class="col-sm-4">
<div class="card h-100">
  <div class="card-body">
  <h2>{{ f.name }}</h2>
  <p>{% for t in f.title %}<span style="font-size: 0.8em;"><em>{{t}}</em></span><br />{% endfor %}</p>
  <img src="/images/faculty/{{ f.photo }}" alt="{{ f.name }}" class="media-object rounded-circle">
  <p style="font-size: 0.9em;">{{ f.profile }}</p>
  {% if f.url != "" %}
  <p><a href="{{ f.url }}"><i class="fas fa-home"></i></a></p>
  {% endif %}
  </div>
</div>
</div>
{% endfor %}

</div>

