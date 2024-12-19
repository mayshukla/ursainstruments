---
layout: default
title: Blog
---
<h1>Blog</h1>

<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }}
  {% endfor %}
</ul>
