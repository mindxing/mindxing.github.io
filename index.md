---
layout: default
nav: false
---
# Vnoel
Musings, thoughts, and (probably bad) ideas

## Recent Posts
{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})
  *{{ post.date | date_to_string }}* — {{ post.tags | join: ", " }}
{% endfor %}
