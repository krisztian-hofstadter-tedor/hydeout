---
layout: page
title: music for the moving image
---


## introduction
Music for the Moving Image allows you to create original music and sound design that _plays_ with poetry, short films and video games using acoustic and computer-based methods of composition. Each assignment provides a variety of options, which can be extended with your own collaborations e.g. with students or professionals from related fields in the wider University or beyond. The practical assignments shall encourage you to develop a range of compositional techniques, using appropriate computer software and hardware in order to become competitive in your career as an artist. Assessment is via the production of a portfolio of the assignments, each accompanied by a succinct commentary.

<ul class="myposts">
{% for post in site.categories.blog reversed %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    </li>
      <hr>
{% endfor %}
</ul>
