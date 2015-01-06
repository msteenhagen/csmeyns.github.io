---
layout: article
title: "Research"
date: 2014-06-25T13:57:25-04:00
modified: 2015-01-05T13:57:25-04:00
excerpt:
tags: [research, philosophy, psychology, metaphysics, early modern, individuation, plasticity, distinction]
image:
  feature: city4.jpg
  teaser: city3.jpg
  thumb: city3.jpg
toc: true
share: false
ads: false
---

My main research is in metaphysics, philosophy of psychology, and early modern philosophy. 

In my work I seek to better understand the structure of experience and how it relates us to things in the world. I am excited about questions concerning forms of experience, the limits of reason and rational explanation, and the way in which the natures of things can be more malleable and plastic than often thought. I pursue this research both historically for the early modern period, as well as in systematic contemporary debates—investigations which I view as interconnected and mutually supporting. 

Currently I am completing a research project on early modern accounts of psychological powers, and am excited to get working on two new ones, as detailed below.

## Projects


#### [The Individuation of the Powers of the Soul](/media/ips)

<figure>
	<img src="/images/brain-1600.jpg">
	<figcaption>Image: <i>Model of a human brain</i> (Europe, 1801-1850), <a href="http://wellcomeimages.org">Wellcome Images</a></figcaption>
</figure>
In _The Individuation of the Powers of the Soul_ (2011-2015) I focus on early modern discussions of the individuation of psychological powers—such as sense perception, thought, and desire. The motivating philosophical puzzle in these discussions is this: It easily seems to us that, for example, seeing a tree is something different from smelling tree, and that both in turn differ from thinking of a tree. But in virtue of what are these capacities of seeing, smelling and thinking different? Are they really distinct at all? In this research I give five case studies of how authors in the early modern period struggle with these and related puzzles. These studies cover work by, among others, Francisco Suárez (1548-1617), Pierre Gassendi (1592-1655), René Descartes (1596-1650), Anne Conway (1631-1679) and Gottfried W. Leibniz (1646-1716). Overall, I establish how changes in metaphysics, as opposed to changes in epistemology or the account of psychological processing, drive the way in which authors in this period distinguish the powers of the mind.

#### Reason and Randomness

<figure>
	<img src="/images/rr-1600.jpg">
</figure>

From chance encounters to risky bets, the notion of probability is crucial in grasping the contingent events around us. Opinions about what is probable guide our belief and action. It is often supposed that concerns about what is probable are in tension with the common rationalist tenet that there is a sufficient reason for any cause. In part because of this, studies on probability have largely ignored a rationalist approach originally found in seventeenth century philosophy, which conceives of reasons as objective facts, and human understanding as continuous with reality. But because it views reasons not as mental figments but as out there in the world, this rationalist approach embodies a take on chance that bridges the persistent gap between subjective and objective interpretations of probability; a gap over which contemporary debates show an ever growing concern. My research project _Reason and Randomness_ (planned 2015-2018) will provide a missing element by examining the rationalist analyses of chance. I will show that, instead of creating a tension, these works contain a viable stance in the theory of probability. I expect this research to contribute to an understanding of the place of reason and chance in early modern and contemporary debates.

#### Substance Plasticity

<figure>
	<img src="/images/plastic-1600.jpg">
	<figcaption>Image: <i>Echo</i> by <a href="https://www.flickr.com/photos/davepatten/511393677">dave patten</a></figcaption>
</figure>

A deep rigidity runs through much current thinking about the metaphysics of substances. In studying sense perception, we assume a fixed set of modalities and streams of sensory information; in capturing action, we begin with distinct moves, projects, and intentions; in defining persistence, we start from a discrete, well-delineated entity. A set division of things in the world is assumed as primitive and basic, waiting to be discovered. In the project _Substance Plasticity_, I reverse the explanatory approach. Drawing on recent studies of in particular transformative experience and neuroplasticity, I argue that metaphysical categories may be more malleable, more plastic than is often supposed. Questioning the standing rigidity is not without consequences. As soon as the idea of a fixed division in metaphysical categories gets questioned, the puzzles themselves will change. Instead of discovering those fixed categories, we need to ask how the appearance of standing distinctions arises in the first place. What confers such apparent stability, what ties it together? I will establish the ground of a new framework for answering these questions. I expect this research to make a defining contribution to the metaphysics of substance.

## Publications

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
