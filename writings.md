---
layout: page
title: Writings
permalink: /writings/
---

# Writings

Essays and thoughts.

{% for writing in site.writings reversed %}
- **[{{ writing.title }}]({{ writing.url }})** — {{ writing.date | date: "%B %d, %Y" }}
{% endfor %}
