---
layout: page
title: UCSD Life
comments: false
---

{% for post in site.posts %}
  {% if post.category == 'dir1' %}
    <div>- {{ post.date | date: "%Y년 %m월 %d일" }} &raquo; [ {{ post.title }} ]({{ post.url }})</div>
  {% endif %}
{% endfor %}
