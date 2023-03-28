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