---
layout: default
title: Home
---

# Informaticawetenschappen BWE6

Welkom bij de cursus informaticawetenschappen!

## Hoofdstukken

{% for page in site.pages %}
  {% if page.path contains 'chapters/' %}
    - [{{ page.title }}]
  {% endif %}
{% endfor %}