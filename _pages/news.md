---
layout: archive
title: "News"
permalink: /news/
author_profile: false
---

{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}
