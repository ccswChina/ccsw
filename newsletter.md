---
layout: page
title: 简报
permalink: /newsletter/
---

## 媒体简报 · 索引  

<div class="posts">

{% assign letter_files = site.static_files | where: "newsletter", true %}

{% for letter in letter_files %}
  <p><a href="{{ site.url }}{{ letter.path }}">{{ letter.basename }}</a></p>
{% endfor %} 

</div>
