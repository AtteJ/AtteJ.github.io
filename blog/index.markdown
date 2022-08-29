---
layout: default
---
# Blogs{% for post in site.posts %}
 
<ul>
 
<li>
    <h3><a href="{{ post.url | relative_url }}">{{ post.date|date: "%d.%m.%Y"  }}  {{ post.title }}</a></h3>
</li>
 
</ul>{% endfor %}
