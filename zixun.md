---
layout: page
title: 资讯
permalink: /zixun/
---


<div class="posts">
    <article class="post">    
      
      {% for post in site.categories.zixun %}
        <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
        <div class="date">
	  {% include post_meta.html %}
        </div>
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>

      {% endfor %}
    </article>
</div>


