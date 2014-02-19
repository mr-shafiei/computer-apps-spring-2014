---
layout: full-width
title: Assignments
---
#Assignments#

<ul class="small-block-grid-1 medium-block-grid-1 large-block-grid-1">
    {% for post in site.categories['assignment'] limit:1 %}
  <li><a href="{{site.baseurl}}/{{ post.url }}">
    <div class="panel callout">
        <h3>{{ post.date | date: "%A" }}</h3>
        <h6><small>{{post.date | date_to_string }}</small></h6>
        <hr>
        <p>{{post.excerpt}}</p>
    </div></a></li>
    {% endfor %}
    {% for post in site.categories['assignment'] offset:1 %}
  <li><div class="panel"><a href="{{site.baseurl}}/{{ post.url }}">{{ post.date | date_to_string }}</a></div></li>
    {% endfor %}
</ul>