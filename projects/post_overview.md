---
title: "Projects"
date: 2023-03-28
---

Projects of the past and present:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Tests:
<ul>
  {% for asset in site.static_files %}
    {% if asset path contains 'projects' %}
    <li>
      <a href="{{ asset.url }}">{{ asset.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>