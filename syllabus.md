---
layout: page
title: syllabus
sidebar_link: true
---

## syllabus

## weekly outline

<ul class="myposts">
{% for post in site.categories.outline reversed %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    </li>
{% endfor %}
</ul>
