---
title: "Posts by Category"
layout: categories
permalink: /categories
author_profile: true
---

{% for category in site.categories %}
  <h3>{{ category | first }}</h3>
{% endfor %}
