---
layout: page
title: Reflections
permalink: /reflections/
---

# Reflections

Work, industry, craft.

{% for reflection in site.reflections reversed %}
- **[{{ reflection.title }}]({{ reflection.url }})** — {{ reflection.date | date: "%B %d, %Y" }}
{% endfor %}
