---
title: Frigid Light Photography
layout: default
---
{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <h4>{{ post.date }}</h4>
{% endfor %}
