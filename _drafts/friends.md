---
layout: page
title: Friends
permalink: /friends/
description: Friends of Purushothaman Pachiappan
path: "/assets/friend/"
---

{% for file in site.static_files %}
{% if file.fri %}
<div style = " margin: 5px;
    border: 1px solid #ccc;
    float: left;
    overflow: auto;
     width: auto;">
     <a target="_blank" href="{{ file.path }}">
  <img src="../{{ file.path }}" alt="{{ file.name }}" width="230" height="150 ">
</a>
<div style=" padding: 15px;
    text-align: center" ><b>{{ file.basename }}</b>
</div>
</div>
{% endif %}
{% endfor %}