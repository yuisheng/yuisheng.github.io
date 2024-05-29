---
layout: default
title: News
---

<h1>News</h1>
<ul>
  {% for post in site.categories.news %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

