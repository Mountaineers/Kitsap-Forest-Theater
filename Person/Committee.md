---
title: Committee
category: List
---
# Committee

### Members

<ul>
  {% for doc in site.pages %}
    {% if doc.category == "Person" %}
      {% if doc.categories contains "Committee" %}
  <li><a href="/Kitsap-Forest-Theater{{ doc.url }}">{{ doc.title }}</a></li>
      {% endif %}
    {% endif %}
  {% endfor %}
</ul>


<sub>The above list is generated from front matter. If 'Committee' is in the `categories` field, the Person will appear in the list.</sub>