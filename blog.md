---
layout: page
title: Blog
permalink: /blog/
---

Welcome to my thoughts on AI, data science, and tech.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
