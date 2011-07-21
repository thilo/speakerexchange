---
layout: default
title: Recent Updates
---

{% for post in site.posts %}
<div class="post">
  <div>
    <h3><span class="created_at">{{post.date | date: "%B %d, %Y"}} &mdash; </span>{{ post.title }}</h3>
    <a class="permalink" href="{{ post.url }}">&raquo; Permalink</a>
  </div>
  <div class="content">
    {{post.content}}
  </div>
</div>
{% endfor %}
