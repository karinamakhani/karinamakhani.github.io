---
layout: default
title: Projects
permalink: /projects/
---

# Projects
<ul class="proj-list">
  {% assign items = site.projects | sort: 'order' %}
  {% for p in items %}
  <li>
    <a class="proj-link" href="{{ p.url | relative_url }}">
      <h3>{{ p.title }}</h3>
      {% if p.meta %}<div class="meta">{{ p.meta }}</div>{% endif %}
      <p>
        {% if p.summary %}{{ p.summary }}
        {% else %}{{ p.excerpt | strip_html | truncate: 160 }}
        {% endif %}
      </p>
    </a>
  </li>
  {% endfor %}
</ul>
