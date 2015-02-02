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
  <P>In <i><a href="/media/ips">The Individuation of the Powers of the Soul</a></i> (2011-2015) I focus on early modern discussions of the individuation of psychological powers—such as sense perception, thought, and desire. The motivating philosophical puzzle in these discussions is this: It easily seems to us that, for example, seeing a tree is something different from smelling tree, and that both in turn differ from thinking of a tree. But in virtue of what are these capacities of seeing, smelling and thinking different? Are they really distinct at all? In this research I give five case studies of how authors in the early modern period struggle with these and related puzzles. These studies cover work by, among others, Francisco Suárez (1548-1617), Pierre Gassendi (1592-1655), René Descartes (1596-1650), Anne Conway (1631-1679) and Gottfried W. Leibniz (1646-1716). Overall, I establish how changes in metaphysics, as opposed to changes in epistemology or the account of psychological processing, drive the way in which authors in this period distinguish the powers of the mind.</P>
  </div>
  <div style="margin:2%">
  <img src="/images/brain-1600.jpg">
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
      <!--   <a href="https://www.researchgate.net/profile/Chris_Meyns" class="btn-warning">ResearchGate</a> -->
        <!-- <a href="PHILPAPERS" class="btn-warning">PhilPapers</a> -->
	<a href="ca.linkedin.com/in/csmeyns" class="btn-social linkedin"><i class="fa fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
       <a href="http://twitter.com/csmeyns" class="btn-social twitter" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i>Twitter</a>
        <a href="{{ site.url }}/feed.xml" class="btn-social rss" target="_blank"><i class="fa fa-rss" aria-hidden="true"></i> RSS</a>
  </div>

