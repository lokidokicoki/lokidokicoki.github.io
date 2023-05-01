---
layout: page
title: Geography
permalink: /geography/
---

The there are two main continents, the Spinwise Marches and the Ripwise Lands

The world map taken from "A traveller's diary by Grundel Hammerkin"

![The World](/assets/full-world-map.jpg)

{% for soc in site.geography %}
{% if soc.continent == "spin" %}
<h3><a href="{{ soc.url }}">{{ soc.title }}</a></h3>
{{ soc.summary }}
{% endif %}
{% endfor %}
