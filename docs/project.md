---
layout: page
title: "Research"
permalink: /project/
---
{% for post in site.categories.project %}
  <h3>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span>{{ post.date | date_to_string }}</span>
  </h3>
  <div>{{ post.excerpt }}</div>
  <br>
{% endfor %}
