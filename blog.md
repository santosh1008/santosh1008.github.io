---
layout: page
title: "Blog"
permalink: /blog/
---

Below are my articles. I write when I learn something new — deep dives, guides, and reflections.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %-d, %Y" }}*
{% endfor %}
