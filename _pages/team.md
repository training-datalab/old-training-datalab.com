---
title: "Training Data Lab - Team"
layout: gridlay
excerpt: "Training Data Lab - Team"
sitemap: false
permalink: /team/
---

# Team Members

**We are  looking for coders to join the Chilean Congress Bills project** [(more info)]({{ site.url }}{{ site.baseurl }}/projects/chilean-congress-bills.html) 

## Core Team
{% assign number_printed = 0 %}
{% for member in site.data.core_team %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {{ member.info1 }}<br>{{ member.info2 }}<br><{{ member.email }}><br>{{ member.website }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Associates
{% assign number_printed = 0 %}
{% for member in site.data.associates %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {{ member.info1 }}<br>{{ member.info2 }}<br><{{ member.email }}><br>{{ member.website }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Extended Team 
<div class="row">

<!-- <div class="col-sm-4 clearfix">
<h4>Research Associates</h4>
{% for member in site.data.associates %}
{{ member.name }}
{% endfor %}
</div>-->

<div class="col-sm-4 clearfix">
<h4>Research Assistants</h4>
{% for member in site.data.assistants %}
{{ member.name }}
{% endfor %}
</div>

<!-- <div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.bachelor %}
{{ member.name }}
{% endfor %}
</div>-->

</div>
