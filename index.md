---
layout: landing
permalink: /
title: "Estonian Scientific Computing Infrastructure"
---

<div class="notice-warning">
	<h3>Estonian Scientific Computing Infrastructure (ETAIS) opens new frontiers for compute- and data-intensive science.</h3>
	<div class="inline-btn">
		<a href="#" class="btn-success"> Learn more</a>
		<a href="https://minu.etais.ee" class="btn-success"> Start using</a>
	</div><!-- /.inline-btn -->
</div>


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
