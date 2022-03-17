---
title: Page Two
---

{% for page in collections.pages %}
- [{{ page.data.title }}]({{ page.url }})
{% endfor %}

This is the second page.