---
layout: page
title: Blog
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    <li style="margin: 10px 0;">
      <a href="{{ post.url }}"> {{ post.date | date_to_string }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

