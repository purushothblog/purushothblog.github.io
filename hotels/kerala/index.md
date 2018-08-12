---
layout: page
description: Hotels in Kerala
---


{% for hotel in site.data.hotelsinkerala %}

<div style = " margin: 5px;
  padding: 8px;
    border: 1px solid #ccc;
    float: left;
    overflow: auto;
     width: auto;">
<a href="/{{ hotel.href }}/{{hotel.page}}">
  <img src="/..{{ hotel.url}}" alt="{{ hotel.key }}" width="340" height="250 ">
</a>
<div style=" padding: 15px;
    text-align: center" ><b>{{ hotel.name }}</b>
</div>
</div>
{% endfor %}