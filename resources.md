---
layout: page
title: resources
sidebar_link: true
permalink: resources
tags:
  - networking
  - resources
  - jobs
---

<ul class="myposts">
{% for post in site.categories.resources reversed %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    </li>
{% endfor %}
</ul>
