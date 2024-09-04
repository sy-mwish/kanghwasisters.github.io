---
title: "24-2프로젝트"
layout: archive
permalink: /categories/24-2-projects/
taxonomy: 24-2프로젝트
author_profile: true
types: posts
---

{% assign posts = site.categories.categories %}
 {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}