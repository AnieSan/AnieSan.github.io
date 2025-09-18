---
layout: post
title: 游戏文章
---


这里是我写的游戏策划相关内容：

<ul>
  {% for game in site.Games %}
    <li><a href="{{ game.url | relative_url }}">{{ game.title }}</a></li>
  {% endfor %}
</ul>
