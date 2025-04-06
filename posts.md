---
layout: default
title: Posts
permalink: /posts/
---
# Posts

{% include navbar.html %}

Here you can find a list of all my posts:

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
