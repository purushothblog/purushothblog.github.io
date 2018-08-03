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
<img src= "{{ dosth.url }}" alt= "{{ dosth.name }}" width="230" height="180" >
 <div style=" padding: 15px;
    text-align: center" ><b>{{ dosth.name }}</b>
</div>
</div>
{% endfor %}