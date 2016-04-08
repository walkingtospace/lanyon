---
layout: page
title: UCSD Life
comments: false
---

{% for post in site.posts %}
  {% if post.category == 'dir1' %}
    - {{ post.date | date: "%Y년 %m월 %d일" }} &raquo; [ {{ post.title }} ]({{ post.url }})
  {% endif %}
  - {{ post.date | date: "%Y년 %m월 %d일" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
