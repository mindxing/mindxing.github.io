---
layout: default
title: "Tag: travel"
---
<h1>Tag: travel</h1>

<ul>
  {% for post in site.tags.travel %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>