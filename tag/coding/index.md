---
layout: default
title: "Tag: coding"
---
<h1>Tag: coding</h1>

<ul>
  {% for post in site.tags.coding %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>