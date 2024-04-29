---
layout: page
title: News
permalink: /news/
---

<ul>
  {% assign reversed_news = site.news | reverse %}
  {% for post in reversed_news %}
    <li style="margin: 10px 0;">
      <a href="{{ post.url }}"> {{ post.date | date_to_string }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>