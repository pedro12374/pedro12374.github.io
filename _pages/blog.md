---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

Welcome to my personal blog. Here I write about updates to this website, my travels, and random thoughts on physics and gaming.

{% for post in site.posts %}
  {% include archive-single.html type="list" %}
{% endfor %}