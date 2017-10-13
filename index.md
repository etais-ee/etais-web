---
layout: landing
permalink: /
title: ""
---

<div class="page-lead" style="background-image:url({{ site.url }}/images/bg.png)">
      <div class="wrap page-lead-content">
        <h3>ETAIS is a National Research Infrastructure of Estonia. It provides infrastructure and application support
	services to the research communities and R&D companies.</h3>
        <a href="self_service/" class="btn-inverse">Self-Service Guide</a> &nbsp; or &nbsp; <a href="start_using/" class="btn-inverse">Start using!</a>
      </div><!-- /.page-lead-content -->
    </div>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
