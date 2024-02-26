---
title: Archives
layout: category
permalink: /categories/archives/
taxonomy: Archives
---

{% assign posts = site.categories.categories %}
 {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}