---
layout: default
---

<h1>欢迎来到我的博客</h1>
<p>这里是我的技术和游戏学习记录。</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
