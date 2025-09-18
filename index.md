---
layout: default
---

<h1>欢迎来到我的博客</h1>
<p>这里是我的技术学习和游戏策划记录。</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
 <!--<p><a href="{{ "/Games/" | relative_url }}">目录</a></p>-->
