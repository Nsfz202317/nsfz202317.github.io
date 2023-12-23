---
layout: default
title: 作业记录 HR
permalink: /categories/HR.html
---

# 作业记录 Homework Record

**图例 Legends**

<span style="margin:0px; font-family:微软雅黑;"><span style="color: #ff0000">●</span> 今交/紧急<br /><span style="color: #00ff00">●</span> 明交<br /><span style="color: #0000ff">●</span> 明不交/延期<br /><span style="color: #ffa0c4">●</span> 周期性</span>

{% for i in site.hr %}
- [{{ i.title }}]({{ i.url }})
{% endfor %}