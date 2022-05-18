---
layout: page
title: Magic & Religion
permalink: /magic-and-religion/
---

## The Siexta

The principle deities of Hyluria are known as the Siexta (^Truar), or the Six (Urman). This group name is found in all languages.

The same deities appear to all races, but in the guise of their race, therefore a Silva^truar praying to Rakshi would see an ancient Silva^truar male.

Of course, there are rumours of other, older (elder, if you will) gods.... But those are just rumours. 


{% for item in site.gods %}
<h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
{{ item.summary }}
{% endfor %}

