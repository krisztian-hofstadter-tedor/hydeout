---
layout: pages
title: outline
sidebar_link: true
---

syllabus

week 1 - week 12 //with anchors, maybe same page, maybe not; 

new text test; 

## Blog

<ul class="post-list">
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a> <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%b %d, %Y" }}</time>
	</li>
	{% endfor %}
</ul>
