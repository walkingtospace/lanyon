---
layout: page
title: [USA] UCSD Life
comments: true
---

{% for post in site.posts %}
  {% if post.category == 'Dir1' %}
  - {{ post.date | date: "%Y년 %m월 %d일" }} &raquo; [ {{ post.title }} ]({{ post.url }})
  {% endif %}
{% endfor %}
