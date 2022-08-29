---
layout: default
title: Blog
description: Posts about my various interests
---
# Posts
{% for post in site.posts %}
 
<ul>
 
<li>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
</li>
 
</ul>{% endfor %}
