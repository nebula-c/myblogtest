---
layout: archive
title: Blog
permalink: /blog/
---



<ul>
  {% for post in site.posts %}
    <li>
      {% if post.categories contains "blog" %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {% endif %}
    </li>
  {% endfor %}
</ul>
