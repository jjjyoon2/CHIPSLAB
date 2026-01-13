---
layout: single
title: "Research"
permalink: /research/
---

Below are our active research directions.

{% for item in site.research %}
- **[{{ item.title }}]({{ item.url | relative_url }})** — {{ item.excerpt | strip_html }}
{% endfor %}
