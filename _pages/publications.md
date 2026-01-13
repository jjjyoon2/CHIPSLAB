---
layout: single
title: "Publications"
permalink: /publications/
---

{% assign pubs = site.publications | sort: "year" | reverse %}
{% for p in pubs %}
- **{{ p.year }}** — {{ p.citation }}
  {% if p.links %}
  ({{ p.links }})
  {% endif %}
{% endfor %}
