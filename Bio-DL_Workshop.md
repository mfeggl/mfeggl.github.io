---
layout: page
title: Bio-DL Workshop
permalink: /Workshops/
---

Find a collection of all the previous workshops here - and watch out for the next edition in 2026!

<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'workshop' %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>