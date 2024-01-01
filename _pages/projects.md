---
layout: page
title: Projects
permalink: /projects/
---

<ul>
  {% for post in site.projects %}
    <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>