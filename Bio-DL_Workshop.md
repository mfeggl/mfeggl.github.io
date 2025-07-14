---
layout: page
title: Bio-DL Workshop
permalink: /tutorials/
---

My tutorials are collected here.  

<ul>
  {% for post in site.posts %}
    {% if post.categories[0] == 'workshop' %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>