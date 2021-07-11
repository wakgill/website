---
layout: default
title: Things Of Interest
---


### Categories...
		
- [Bitcoin](/bitcoin)
- [Fiction](/fiction)
- [Meta](/meta)

### Latest updates

{% for post in site.posts %}
  <li>{{ post.date | date: "%Y-%m-%d" }}: <a href="{{ post.url }}">{{ post.title }}</a> </li>
{% endfor %}

### External links

- Twitter: [@dontusetwitter](/)
