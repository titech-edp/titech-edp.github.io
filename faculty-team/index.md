---
layout: page
title: 教員チームの紹介
---

<div class="row row-eq-height">

{% for f in site.data["faculty"] %}
<div class="col-md-4 panel panel-default">
  <div class="panel-body">
  <h2>{{ f.name }}</h2>
  <p>{% for t in f.title %}<span style="font-size: 0.8em;"><em>{{t}}</em></span><br />{% endfor %}</p>
  <img src="/images/faculty/{{ f.photo }}" alt="{{ f.name }}" class="media-object img-circle">
  <p style="font-size: 0.9em;">{{ f.profile }}</p>
  {% if f.url != "" %}
  <p><a href="{{ f.url }}"><span class="glyphicon glyphicon-home" aria-hidden="true"></span></a></p>
  {% endif %}
  </div>
</div>
{% endfor %}

</div>
