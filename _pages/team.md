---
title: "Training Data Lab - Team"
layout: gridlay
excerpt: "Training Data Lab - Team"
sitemap: false
permalink: /team/
---

# Team Members

<a href="https://training-datalab.com/resources"><strong>Resources for our team</strong>.</a>

## Coordinator
{% assign number_printed = 0 %}
{% for member in site.data.coordinator %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <br>{{ member.name }}<br>
  {{ member.info }}<br>{{ member.website }}
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

## Research Associates
{% assign number_printed = 0 %}
{% for member in site.data.associates %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <!-- <h4>{{ member.name }}</h4> -->
  <br>{{ member.name }}<br>
  <!-- {{ member.info }}<br><{{ member.email }}><br>{{ member.website }}-->
  {{ member.info }}<br>{{ member.website }}
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

## Adjunct Researchers
{% assign number_printed = 0 %}
{% for member in site.data.adjuncts %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <!-- <h4>{{ member.name }}</h4> -->
  <br>{{ member.name }}<br>
  <!-- {{ member.info }}<br><{{ member.email }}><br>{{ member.website }}-->
  {{ member.info }}<br>{{ member.website }}
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

## Research Assistant
{% assign number_printed = 0 %}
{% for member in site.data.research_assistants %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <!-- <h4>{{ member.name }}</h4> -->
  <br>{{ member.name }}<br>
  <!-- {{ member.info }}<br><{{ member.email }}><br>{{ member.website }}-->
  {{ member.info }}<br>{{ member.website }}
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

## Former Assistants
<div class="row">

<div class="col-sm-4 clearfix">

{% for member in site.data.assistants1 %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
{% for member in site.data.assistants2 %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
{% for member in site.data.assistants3 %}
{{ member.name }}
{% endfor %}
</div>

</div>
