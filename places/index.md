---
layout: default
title: Places
---
# {{ page.title }}

{% for place in site.places %}
* [{{ place.name }} test]({{ place.url }})
{% endfor %}