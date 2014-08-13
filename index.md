---
layout: home
top: chris meyns
center: Chris Meyns
tagline: I’m a philosopher, I work on metaphysics and philosophy of psychology, and am based at University College London (UCL).
permalink: /
image:
  feature: marble-texture-1600x800.jpg
---

<div class="tiles">

{% for post in site.categories.articles limit:3 %}
<div class="tile">
<a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}" class="post-teaser">{% if post.image.teaser %}<img src="{{ site.url }}/images/{{ post.image.teaser }}" alt="teaser" itemprop="image">
    {% else %}<img src="{{ site.url }}/images/{{ site.teaser }}" alt="teaser" itemprop="image">{% endif %}</a>
  {% if post.date %}<p class="entry-date date published"><time datetime="{{ post.date | date: "%Y-%m-%d" }}" itemprop="datePublished">{{ post.date | date: "%B %d, %Y" }}</time></p>{% endif %}
  <h2 class="post-title">{{ post.title }}</h2>
  <p class="post-excerpt">{{ post.excerpt }}</p>
  </div><!-- /.tile -->
{% endfor %}

{% for post in site.categories.publications limit:1 %}
<div class="tile">
<a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}" class="post-teaser">{% if post.image.teaser %}<img src="{{ site.url }}/images/{{ post.image.teaser }}" alt="teaser" itemprop="image">
    {% else %}<img src="{{ site.url }}/images/{{ site.teaser }}" alt="teaser" itemprop="image">{% endif %}</a>
  {% if post.date %}<p class="entry-date date published"><time datetime="{{ post.date | date: "%Y-%m-%d" }}" itemprop="datePublished">{{ post.date | date: "%B %d, %Y" }}</time></p>{% endif %}
  <h2 class="post-title">{{ post.title }}</h2>
  <p class="post-excerpt">{{ post.excerpt }}</p>
  </div><!-- /.tile -->
{% endfor %}

</div><!-- /.tiles -->
