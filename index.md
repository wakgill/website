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
  * {{ post.date | date_to_string }}: [ {{ post.title }} ]({{ post.url }})
{% endfor %}

### External links

- Twitter: [@dontusetwitter](/)
