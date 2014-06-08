---
layout: page
title: All
tagline: Supporting tagline
---
{% include JB/setup %}
<style>
.logo{ width:250px; height:60px; background-size:260px 60px; margin-top:0;}
.banner{ display:none}
@media screen and (min-width: 900px) {
.menu .item{ border-top:none;}
}
</style>
<div class="bodyarea">
  <div class="bodylist">

<ul class="posts">
  {% for post in site.posts %}
    <li class="item"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}/sportsnews{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

 </div>
</div>