---
layout: page
title: Geography
permalink: /geography/
---

The there are two main continents, the Spinwards Marches and the Ripwise Lands

The world map taken from "A traveller's diary by Grundel Hammerkin"

![The World](/assets/full-world-map.jpg)

<h2>Spinwards Marches</h2>

{% for soc in site.geography %}
{% if soc.continent == "spin" %}
<h3><a href="{{ soc.url }}">{{ soc.title }}</a></h3>
{{ soc.summary }}
{% endif %}
{% endfor %}

<h2>Ripwise Lands</h2>

{% for soc in site.geography %}
{% if soc.continent == "rip" %}
<h3><a href="{{ soc.url }}">{{ soc.title }}</a></h3>
{{ soc.summary }}
{% endif %}
{% endfor %}

<h2>Other</h2>

{% for soc in site.geography %}
{% if soc.continent == "other" %}
<h3><a href="{{ soc.url }}">{{ soc.title }}</a></h3>
{{ soc.summary }}
{% endif %}
{% endfor %}
