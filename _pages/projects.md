---
layout: page
title: Projects
permalink: /projects/
---

In the course of my studies, I have been involved in multiple projects:

<ul>

  {% for post in site.projects %}
  <li style="margin: 15px 0;">
    <a href="{{ post.url }}"> {{ post.title }} </a>
  </li>
  {% endfor %}

</ul>