---
layout: page
title: Projects
permalink: /projects/
tags: topnav
---

#Cac du an dang trien khai

Noi dung viet o day.

<ul>
	{% for page in site.pages %}
	{% if page.tags == "project" %}
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
	{% endif %}
	{% endfor %}
</ul>