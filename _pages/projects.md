---
title: "Training Data Lab - Projects"
layout: gridlay
excerpt: "Training Data Lab - Projects"
sitemap: false
permalink: /projects/
---

# Projects

{% assign number_printed = 0 %}
{% for publi in site.data.projects %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit><a href="{{ publi.link.url }}">{{ publi.title }}</a></pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/projects/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p align="justify">{{ publi.description }}</p>
  <p>By {{ publi.authors }}</p>
  <!-- <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>-->
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
