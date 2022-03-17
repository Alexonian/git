---
title: My First Eleventy Site
layout: base.njk
---


## Macaroon brownie carrot pie


{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{% endfor %}