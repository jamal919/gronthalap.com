---
layout: default
---

<div>
  {% for post in site.posts %}
      <a href="{{ post.url }}"><h1>{{ post.title }}</h1></a>
      {{ post.excerpt }}
  {% endfor %}
</div>
