---
layout: archive
title: Blog
permalink: /blog/
---



<ul>
  {% for posts in site.posts %}
    <li>
      {{ post.categories }}
      {%
      {% if post.categories contains "blog" %}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      {% endif %}
      %}
    </li>
  {% endfor %}
</ul>
