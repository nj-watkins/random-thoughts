---
title: Posts about math.
permalink: /math-posts/
sidebar: true
---
{% for post in site.posts %}
  {% if post.tags contains 'math' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}