---
permalink: /past_concerts/
title: Bisherige Konzerte
ref: past_concerts
---

<h1>Bisherige Konzerte</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>