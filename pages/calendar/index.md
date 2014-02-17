---
layout: full-width
title: Calendar
---
#Calendar#

<ul class="small-block-grid-1 medium-block-grid-3 large-block-grid-5">
    {% for post in site.categories['calendar'] limit:1 %}
  <li><a href="{{ post.url }}">
    <div class="panel callout">
        <h3>{{ post.date | date: "%A" }}</h3>
        <h6><small>{{post.date | date_to_string }}</small></h6>
        <hr>
        <p>{{post.excerpt}}</p>
    </div></a></li>
    {% endfor %}
    {% for post in site.categories['calendar'] offset:1 %}
  <li><a href="{{ post.url }}">
    <div class="panel">
        <h3>{{ post.date | date: "%A" }}</h3>
        <h6><small>{{post.date | date_to_string }}</small></h6>
        <hr>
        <p>{{post.excerpt}}</p>
    </div></a></li>
    {% endfor %}
</ul>