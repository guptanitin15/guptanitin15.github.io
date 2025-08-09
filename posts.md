---
layout: archive
title: "Blog"
permalink: /posts/
author_profile: true
---

{% for post in paginator.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include paginator.html %}
