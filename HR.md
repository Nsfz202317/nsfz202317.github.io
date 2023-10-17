---
layout: default
title: 作业记录 HR
permalink: /categories/HR.html
---

# 作业记录 Homework Record

{% for i in site.hr %}
- [{{ i.title }}]({{ i.url }})
{% endfor %}