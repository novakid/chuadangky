---
layout: page
title: Blog
permalink: /blog/
tags: topnav
---

<div class="row">
  <div class="columns">
    <ul>
    {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li
    {% endfor %}
    </ul>
  </div>
</div>
