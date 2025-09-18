---
layout: default
title: 游戏
---

<h1>游戏策划目录</h1>

<ul>
{% for post in site.games %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
