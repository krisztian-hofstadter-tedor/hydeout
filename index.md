---
layout: page
title: music for the moving image
---

Exploring   
the relationship   
between music and the moving image,   
sound and vision.

<br>

## Blog

<ul class="myposts">
{% for post in site.categories.blog reversed %}
    <li>{{ post.date | date: "%F" }} | <a href="{{ post.url }}">{{ post.title}}</a>
    <br>
    </li>
      <hr>
{% endfor %}
</ul>

`loading...`

<br>

by [K.Hofstadter](https://khofstadter.info)
