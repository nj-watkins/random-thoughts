---
title: Posts about programming.
permalink: /programming-posts/
sidebar: true
---

{% for post in site.posts %}
  {% if post.tags contains 'programming' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
