---
layout: page
title: All
tagline: Supporting tagline
---
{% include JB/setup %}

<div class="bodyarea">
  <div class="bodylist">

<ul class="posts">
  {% for post in site.posts %}
    <li class="item"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}/sportsnews{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

 </div>
</div>