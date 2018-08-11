---
layout: page
description: Hotel and Rooms in Tamil Nadu
permalink: /hotel/tamilnadu/
---

{% for state in site.data.states %}

<div style = " margin: 5px;
  padding: 8px;
    border: 1px solid #ccc;
    float: left;
    overflow: auto;
     width: auto;">
<a target="_blank" href="/{{ state.name }}/">
  <img src="/..{{ state.url}}" alt="{{ state.name }}" width="340" height="250 ">
</a>
<div style=" padding: 15px;
    text-align: center" ><b>{{ state.name }}</b>
</div>
</div>
{% endfor %}


