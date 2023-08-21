---
layout: default
title: Publications
permalink: /publications
---

<div style = "text-align:center">
<img src="{{site.url}}{{site.baseurl}}/images/publications.png" alt="Publications">
</div>

## In Prep
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=in prep] %}
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=accepted pending data collection] %}
<br>

## Under Review
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=under review] %}
<br>

## In Press
 {% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=in press] %}
<br>

{% for year in (2006..2023) reversed %}
<h2>{{year}}</h2>
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year={{year}}] %}
<br>
{% endfor %}

## 2003
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=2003] %}
<br>

## 2001
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=2001] %}
<br>

## UnPublished Manuscript
{% bibliography --template bibtemplate --style _bibliography/langcog.csl --query @*[year=unpublished manuscript] %} 




