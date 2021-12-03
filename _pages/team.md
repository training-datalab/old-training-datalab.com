---
title: "Training Data Lab - Team"
layout: gridlay
excerpt: "Training Data Lab - Team"
sitemap: false
permalink: /team/
---

# Team Members

<!-- **We have an open call for research assistants** <a href="https://github.com/training-datalab/workshops/blob/main/Calls/Call-Data-Lab-Spanish.pdf" target="_blank">(see in Spanish)</a> -->

Here is our <a href="https://training-datalab.slack.com" target="_blank"><strong>#Slack workspace</strong></a> for our team.

## Researchers
{% assign number_printed = 0 %}
{% for member in site.data.researchers %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/team/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {{ member.info }}<br><{{ member.email }}><br>{{ member.website }}
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
  <h4>{{ member.name }}</h4>
  {{ member.info }}<br><{{ member.email }}><br>{{ member.website }}
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

<!-- ## Associates
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
{% endif %}-->

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
