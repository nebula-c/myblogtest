---
layout: archive
title: Blog
permalink: /blog/
---



<ul>
  {% for post in site.posts %}
    {% if post.categories contains "blog" %}
      {li}
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </li>  
    {% endif %}
  {% endfor %}
</ul>
