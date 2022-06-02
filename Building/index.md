---
title: Buildings
category: List
---

# Buildings

<ul style="list-style: none;">
  {% for doc in site.pages %}
    {% if doc.category == "Building" %}
      <li><a href="/Kitsap-Forest-Theater{{ doc.url }}">{{ doc.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
