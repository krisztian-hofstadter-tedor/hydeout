---
layout: page
title: syllabus
sidebar_link: true
---

<ul class="myposts">
{% for post in site.categories.outline reversed %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    </li>
    {% if post.excerpt %}
      {{ post.excerpt }}
    {% else %}
      {{ post.content }}
    {% endif %}
{% endfor %}
</ul>


---

Due to different student experience and expectations, this outline can be subject to change. Detailed notes for each week will be added gradually to this website.
