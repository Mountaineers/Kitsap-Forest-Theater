---
title: Persons
category: List
---

<div style="width: 60%; float: right; text-align: center;">
  <h3>Persons</h3>
  <div style="text-align: left; column-count: 2;">
    <ul style="list-style: none;">
      {% assign persons = site.pages | sort: "title" %}
      {% for doc in persons %}
        {% if doc.category == "Person" %}
          <li><a href="/Kitsap-Forest-Theater{{ doc.url }}">{{ doc.title }}</a></li>
        {% endif %}
      {% endfor %}
    </ul>
  </div>
</div>

### Lists / Roles

* [Chair](Chair)
* [Committee](Committee)
* [Cook](Cook)
* [Historian](Historian)
