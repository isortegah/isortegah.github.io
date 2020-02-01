---
layout: page
title: Blog
permalink: /blog/
---
<link rel="stylesheet" href="{{ "/assets/css/blog.css" | relative_url }}">
<div class="blog">
<ul>
  {% for post in site.posts %}
    <li class="liBlog">
      <a href="{{ post.url }}" class="titlePost">{{ post.title }}</a>  <br><div class="datePost">{{ post.date | date: "%a, %b %d, %y"}}</div>
      {{ post.excerpt }} 
      <div class="seccMas">
      <a href="{{ post.url }}" class="more">Más ...</a>
      </div>
    </li>
  {% endfor %}
</ul>
</div>