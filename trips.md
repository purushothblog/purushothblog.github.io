---
layout: page
title: Trips
permalink: /trips/
---


Thumbs of my trips
{% for file in site.static_files %}
{% if file.image %}
<div style = " margin: 5px;
    border: 1px solid #ccc;
    float: left;
     width: auto;
    height: auto;">
  <a target="_blank" href="{{ file.path }}">

   <img src="../{{ file.path }}" alt="{{ file.name }}" width="230" height="150" >
</a>
    <div style=" padding: 15px;
    text-align: center" >{{ file.name }}
</div>
</div>
{% endif %}
{% endfor %}
<div>
	<br>
<hr>
<h2> Stay tune for more fun! </h2>
</div>