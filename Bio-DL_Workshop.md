---
layout: page
title: Bio-DL Workshop
permalink: /Workshops/
---

My tutorials are collected here.

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'workshop' %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>