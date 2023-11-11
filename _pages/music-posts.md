---
title: Posts about music.
permalink: /music-posts/
sidebar: true
---

{% for post in site.posts %}
  {% if post.tags contains 'music' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
