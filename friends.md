---
layout: page
title: Friends
permalink: /friends/
description: Friends of Purushothaman Pachiappan
---

{% for dosth in site.data.friends %}
<div style = " margin: 5px;
    border: 1px solid #ccc;
    float: left;
    overflow: auto;
     width: auto;">
     <a target="_blank" href="{{ dosth.url }}">
<img src="../{{ dosth.url }}" alt="{{ dosth.name }}" width="230" height="150 ">
</a>
 <div style=" padding: 15px;
    text-align: center" ><b>{{ dosth.name }}</b>
</div>
</div>
{% endfor %}