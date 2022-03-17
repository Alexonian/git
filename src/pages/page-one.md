---
title: Page One
---
{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{% endfor %}

This is the first page.

