---
layout: page
title: Miscellaneous
permalink: /misc/
---

{% for item in site.misc %}
<h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
{{ item.summary }}
{% endfor %}