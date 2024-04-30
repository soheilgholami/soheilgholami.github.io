---
layout: page
title: Projects
permalink: /projects/
---

I have been involved in the following projects (the list is arranged in descending order, starting with the most recent project):

<ul>

  {% assign reversed_projects = site.projects | reverse %}
  {% for post in reversed_projects %}
  <li style="margin: 15px 0;">
    <a href="{{ post.url }}"> {{ post.title }} </a>
  </li>
  {% endfor %}

</ul>