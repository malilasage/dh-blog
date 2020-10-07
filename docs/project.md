---
layout: page
title: "Project"
permalink: /project/
---
{% for post in site.categories.project %}
 <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
