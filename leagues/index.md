---
title: "League Rankings"
---

{% for doc in site.pages %}
{% if doc.category == "league" %}

- [{{ doc.title }}]({{ doc.url }})
  {% endif %}
  {% endfor %}
