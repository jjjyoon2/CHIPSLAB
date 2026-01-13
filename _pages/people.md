---
layout: single
title: "People"
permalink: /people/
---

{% for person in site.people %}
### {{ person.name }}
- Role: {{ person.role }}
- Interests: {{ person.interests }}
{% if person.links %}
- Links: {{ person.links }}
{% endif %}

{% endfor %}
