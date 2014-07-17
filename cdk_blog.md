---
layout: page
title: Blog
permalink: /blog/
tags: topnav
weight: 3
---

<div class="row">
  <div class="columns">
    <ul>
    {% for post in site.posts %}
    <li><a href="{{ site.baseurl}}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
  </div>
</div>
