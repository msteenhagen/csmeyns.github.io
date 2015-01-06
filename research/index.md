---
layout: article
title: "Research and publications"
date: 2014-06-25T13:57:25-04:00
modified:
excerpt:
tags: []
image:
  feature:
  teaser:
  thumb:
toc: true
share: false
ads: false
---

<!-- # Research statement-->

<!-- Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. -->

# Publications

<div class="tiles">
{% for post in site.categories.publications %}
<p>{% if post.year != "forthcoming" %}
<span class="badge success">{{ post.year }}</span>
{% else %}
<span class="badge warning">Forthcoming</span>
{% endif %}, 
<a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>, in <em>{{ post.journal }}</em>{% if post.volume %} {{ post.volume }}{% if post.issue %}:{{ post.issue }}{% endif %}{% endif %}. {% if post.doi %}<small>DOI:</small>{{ post.doi }}{% endif %} {% if post.link %}<small><a href="{{ post.link }}" target="_blank">(view online)</a></small>{% endif %}
</p>

{% endfor %}
</div><!-- /.tiles -->
