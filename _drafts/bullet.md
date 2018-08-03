---
layout: default
title: bullets
description: Where else can you find me online?
---

{% for bullet in site.static_files %}
{% if bullet.image %}

  <div>
  	<div style=" border: 1px solid #ccc; float: left;
  width: 30%;
  padding: 5px;">
  <a target="_blank" href="{{ bullet.path }}">
  <img src=" {{bullet.path}}" alt="{{ bullet.name}}" width="230" height="150">
  </a>
  <div style=" padding: 15px;
    text-align: center" ><b>{{ bullet.basename }}</b>
  </div>
    </div>
  </div>
{% endif %}
{% endfor %}
