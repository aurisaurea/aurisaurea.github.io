---
permalink: /past_concerts/
title: Bisherige Konzerte
ref: past_concerts
---

<ul>
  {% for post in site.past_concerts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>