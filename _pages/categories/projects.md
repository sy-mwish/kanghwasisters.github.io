---
title: 프로젝트
layout: category
permalink: /categories/projects/
taxonomy: 프로젝트
---

{% assign posts = site.categories.categories %}
 {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}