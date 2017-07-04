---
layout: page
title: 教員チームの紹介
---

<div class="row">

{% for f in site.data["faculty"] %}
<div class="col-md-12 panel panel-default">
  <div class="panel-body">
  <h2>{{ f.name }}</h2>
  <p>{% for t in f.title %}<em>{{t}}</em><br />{% endfor %}</p>
  <img src="/images/faculty/{{ f.photo }}" alt="{{ f.name }}" class="media-object img-circle">
  <p>{{ f.profile }}</p>
  <p><a href="{{ f.url }}">{{ f.url }}</a></p>
  </div>
</div>
{% endfor %}

</div>
