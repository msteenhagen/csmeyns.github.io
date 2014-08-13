---
layout: archive
title: "Publications"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "Recent work that appeared"
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.publication %}
  
<p>{{ post.year }}, <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>, in <em>{{ post.journal }}</em> {% if post.volume %}{{ post.volume }}{% if post.issue %}:{{ post.issue }}{% endif %}{% endif %} {% if post.doi %}<small>DOI:</small>{{ post.doi }}{% endif %} {% if post.link %}<small><a href="{{ post.link }}" target="_blank">(view online)</a></small>{% endif %}
</p>

{% endfor %}
</div><!-- /.tiles -->