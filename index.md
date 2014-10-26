---
layout: default
title: Ng Cheuk-fung
---
<div id="home">
  <h1>Recent Posts</h1>
  <ul class="posts">
    {% for post in site.posts limit:10 %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
