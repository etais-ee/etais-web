---
layout: landing
permalink: /
title: "Estonian Scientific Computing Infrastructure (ETAIS)"
---

<div class="notice-info">
	<h3>ETAIS is a National Research Infrastructure of Estonia. It provides infrastructure and application support
	services to the research communities and R&D companies.</h3>
	<div class="inline-btn">
		<a href="self_service/" class="btn-success"> Self-Service Guide</a>
		<a href="start_using/" class="btn-success"> Start using!</a>
	</div><!-- /.inline-btn -->
</div>


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
