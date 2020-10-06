---
layout: page
title: "Project"
permalink: /project/
---
{% for post in site.categories.project %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
