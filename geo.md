---
layout: page
title: Geography
permalink: /geography/
---

The there are two main continents, the Spinwise Marches and the Ripwise Lands

{% for soc in site.geography %}
<h2><a href="{{ soc.url }}">{{ soc.title }}</a></h2>
{{ soc.summary }}
{% endfor %}