---
layout: page
title: Gallery
permalink: /gallery/
description: Purushothaman Pachiappan, Gallery | Bike Tour
---


<center><h3><b><u>Diaries of My Life</u></b></h3></center>

{% for file in site.static_files %}
{% if file.image %}
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
</div></div>
{% endif %}
{% endfor %}


<br>
<table>
	<tr>
		<td>
<h2 align="center"><marquee> <u>Stay tune for more fun!</u> </marquee></h2></td>


</tr></table>