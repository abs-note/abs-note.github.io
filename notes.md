---
layout: page
title: 全部笔记
permalink: /notes.html
---
{% for post in site.posts %}
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})
  > 分类：{{ post.categories | join: ', ' }}
{% endfor %}