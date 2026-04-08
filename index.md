---
layout: default
nav: false
---
# Welcome to my site!
This is my hand-crafted blog v2.

## Recent Posts
{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})
  *{{ post.date | date_to_string }}* — {{ post.tags | join: ", " }}
{% endfor %}
