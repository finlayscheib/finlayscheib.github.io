---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Welcome to my thoughts on AI, data science, and math. This is where I ramble on about my thoughts. Please excuse any spelling mistakes and please reach out if you wish to discuss further. These posts are non-technical, and hopefully cater to all.

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) — *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}

[← Back to Homepage](/)
