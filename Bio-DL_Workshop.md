---
layout: page
title: Bio-DL Workshop
permalink: /Workshops/
---

{% assign upcoming = site.posts | where_exp: "post",
  "post.categories contains 'workshop' and post.upcoming == true"
  | sort: "date" | reverse | first %}

{% assign past_workshops = site.posts | where_exp: "post",
  "post.categories contains 'workshop' and post.upcoming == false"
  | sort: "date" | reverse %}

The next **Bio-inspired Deep Learning Workshop** will take place in **2026**.
Details about the upcoming edition can be found in the latest workshop announcement:

<a href="{{ upcoming.url }}">{{ upcoming.title }}</a>.

Below you can find a collection of **previous workshops** in this series.

<ul>
  {% for post in past_workshops %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>