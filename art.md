---
layout: page
title: Art
permalink: /art/
---

# Art

Photography, drawing, painting.

{% for piece in site.art reversed %}
- **[{{ piece.title }}]({{ piece.url }})** — {{ piece.date | date: "%B %d, %Y" }}
{% endfor %}
