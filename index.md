---
layout: home
top: chris meyns
center: Chris Meyns
tagline: 
permalink: /
image:
  feature: city3.jpg
---

<div class="tiles">

{% for post in site.categories.articles limit:3 %}
<div class="tile">
<a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}" class="post-teaser">{% if post.image.teaser %}<img src="{{ site.url }}/images/{{ post.image.teaser }}" alt="teaser" itemprop="image">
    {% else %}<img src="{{ site.url }}/images/{{ site.teaser }}" alt="teaser" itemprop="image">{% endif %}</a>
  {% if post.date %}<p class="entry-date date published"><time datetime="{{ post.date | date: "%Y-%m-%d" }}" itemprop="datePublished">{{ post.date | date: "%B %d, %Y" }}</time></p>{% endif %}
  <h2 class="post-title"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h2>
  <p class="post-excerpt">{{ post.excerpt }}</p>
  </div><!-- /.tile -->
{% endfor %}

{% for post in site.categories.publications limit:1 %}
<div class="tile">
<a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}" class="post-teaser">{% if post.image.teaser %}<img src="{{ site.url }}/images/{{ post.image.teaser }}" alt="teaser" itemprop="image">
    {% else %}<img src="{{ site.url }}/images/{{ site.teaser }}" alt="teaser" itemprop="image">{% endif %}</a>
  {% if post.date %}<p class="entry-date date published"><time datetime="{{ post.date | date: "%Y-%m-%d" }}" itemprop="datePublished">{{ post.date | date: "%B %d, %Y" }}</time></p>{% endif %}
  <h2 class="post-title"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h2>
  <p class="post-excerpt">{{ post.excerpt }}</p>
  </div><!-- /.tile -->
{% endfor %}

</div><!-- /.tiles -->

<table>
  <thead>
    <tr>
      <th style="text-align: left"><h4>Featured project</h4></th>
    </tr>
  </thead>
  </table>
<div style="float:left; margin:2%">
  <P>In <i><a href="/media/ips">A deep rigidity runs through much current thinking about the metaphysics of substances. In studying sense perception, we assume a fixed set of modalities and streams of sensory information; in capturing action, we begin with distinct moves, projects, and intentions; in defining persistence, we start from a discrete, well-delineated entity. A set division of things in the world is assumed as primitive and basic, waiting to be discovered. In the project Substance Plasticity, I reverse the explanatory approach. Drawing on recent studies of in particular transformative experience and neuroplasticity, I argue that metaphysical categories may be more malleable, more plastic than is often supposed. Questioning the standing rigidity is not without consequences. As soon as the idea of a fixed division in metaphysical categories gets questioned, the puzzles themselves will change. Instead of discovering those fixed categories, we need to ask how the appearance of standing distinctions arises in the first place. What confers such apparent stability, what ties it together? I will establish the ground of a new framework for answering these questions. I expect this research to make a defining contribution to the metaphysics of substance.</P>
  </div>
  <div style="margin:2%">
  <img src="/images/plastic-1600.jpg">
  </div>
 <!--  <img src="//mmistakes.github.io/skinny-bones-jekyll/images/image-filename-1.jpg" title="TEXT"> -->
<!--   <figcaption></figcaption> -->



<div>

<table>
  <thead>
    <tr>
      <th style="text-align: left"><h4>Upcoming</h4></th>
      <th style="text-align: center"></th>
      <th style="text-align: right"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">April 9-11, 2015</td>
      <td style="text-align: center">Gradual Perceptual Difference</td>
      <td style="text-align: right"><a href="http://www.bshp.org.uk/home" target="_blank">British Society for the History of Philosophy</a></td>
    </tr>
    <tr>
      <td style="text-align: left">May 27-29, 2015</td>
      <td style="text-align: center">Leibniz on the Ethics of Probability</td>
      <td style="text-align: right"><a href="http://scientiae.co.uk/?page_id=740" target="_blank">Scientiæ 2015</a></td>
    </tr>
      <tr>
      <td style="text-align: left">July 3-5, 2015</td>
      <td style="text-align: center">Leibniz on the Ethics of Probability</td>
      <td style="text-align: right"><a href="http://www.leibniz-translations.com/leibniz2015.htm" target="_blank">Leibniz - Scientist, Leibniz - Philosopher</a></td>
    </tr>
  </tbody>
</table>
</div>



<div class="tiles">
<div class="tile">
  <h5>Get in touch</h5>
  <p><a href="mailto:c.s.meyns@gmail.com">c.s.meyns <i>at</i> gmail.com</a></p>
  <p>Philosophy, University of Toronto, 170 St. George Street, M5R 2M8, Toronto, ON, Canada</p></div>
  <div class="tile">
  <h5>Follow</h5>
        <a href="http://ucl.academia.edu/CSMeyns" class="btn-success" target="_blank">Academia</a>
        <a href="http://scholar.google.com/citations?hl=en&user=KuAxKHEAAAAJ" target="_blank" class="btn-info">Google scholar</a>
        <!-- <a href="PHILPAPERS" class="btn-warning">PhilPapers</a> -->
	<a href="http://ca.linkedin.com/in/csmeyns" target="_blank" class="btn-social linkedin"><i class="fa fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
       <a href="http://twitter.com/csmeyns" class="btn-social twitter" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i>Twitter</a>
        <a href="{{ site.url }}/feed.xml" class="btn-social rss" target="_blank"><i class="fa fa-rss" aria-hidden="true"></i> RSS</a>
  </div>

