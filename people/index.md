---
layout: default
title: People
---
# {{ page.title }}
test2

{% for person in site.people %}
  <h2>
    <a href="{{ person.url }}">
      {{ person.name }}
    </a>
  </h2>
{% endfor %}
