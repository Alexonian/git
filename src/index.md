---
title: My First Eleventy Site
layout: base.njk
---


## Macaroon brownie carrot poo



{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{% endfor %}