```
---
title: "MySQL 학습"
layout: archive
permalink: /sql/
---


{% assign posts = site.categories.sql %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
```