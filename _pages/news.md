---
layout: archive
title: "News"
permalink: /news/
classes: wide
author_profile: false
---

{% for post in site.posts limit: 5 %}
  {% include archive.html %}
{% endfor %}