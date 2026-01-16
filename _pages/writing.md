---
layout: archive
title: "Writing"
collection: writing
permalink: /writing/
---

{% for x in site.writing %}
- {{ x.title }} ({{ x.url }})
{% endfor %}

