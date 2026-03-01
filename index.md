---
layout: home
title: Home
---
# Welcome to My Blog

Here you’ll find all my latest posts.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
