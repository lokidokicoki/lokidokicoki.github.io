---
layout: page
title: Demographics
permalink: /demographics/
---

The principle races of Hyluria

{% for soc in site.races %}
<h2><a href="{{ soc.url }}">{{ soc.title }} ({{ soc.d5e }})</a></h2>
{{ soc.summary }}
{% endfor %}