---
layout: archive
title: Blog
permalink: /blog/
---



<ul>
  {% for posts in site.posts %}
    <li>
      {{ post.categories }}
    </li>
  {% endfor %}
</ul>
