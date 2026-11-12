---
layout: home
permalink: research
title: "Research Projects"
excerpt: " <br> <br>"
image:
  feature: 20150613_074.jpg
---
<h2 class="post-title"> </h2>
<div class="tiles">
{% for post in site.categories.research %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
