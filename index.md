---
layout: default
title: quakpot ideas
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title | downcase }}</a>
    </li>
  {% endfor %}
</ul>


