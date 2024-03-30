---
layout: default
title: 作业记录 HR
permalink: /categories/HR.html
---

# 作业记录 Homework Record

**图例 Legends**

<span style="margin:0px; font-family:微软雅黑;"><span style="color: #ff0000">●</span> 今交/紧急<br /><span style="color: #00ff00">●</span> 明交<br /><span style="color: #0000ff">●</span> 明不交/延期<br /><span style="color: #ffa0c4">●</span> 周期性</span>

{% for i in site.hr reversed %}
<li><a href="{{ i.url }}">{{ i.title }}</a></li>
{% endfor %}

<!--{% assign asc = 1 %}

按时间 <button id="ascBut" style="" onclick="asc()">正序</button><button id="descBut" style="" onclick="desc()">倒序</button> 排序

<div id="listHR">
<ul>
{% if asc==1 %}
{% for i in site.hr %}
<li><a href="{{ i.url }}">{{ i.title }}</a></li>
{% endfor %}
{% else %}
{% for i in site.hr reversed %}
<li><a href="{{ i.url }}">{{ i.title }}</a></li>
{% endfor %}
{% endif %}
</ul>
</div>

<script type="text/javascript">
    function asc() { {% assign asc = 1 %} ; console.log( {{ asc }} ); $("listHR").load(location.href+" #listHR");}
    function desc() { {% assign asc = 0 %} ; console.log( {{ asc }} ); $("listHR").load(location.href+" #listHR");}
</script>-->