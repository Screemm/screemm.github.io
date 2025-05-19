---
title: Changelog
layout: home
nav_order: 1
parent: Dev Notes
---

Below is a complete list of changelogs, sorted by newest to oldest.

{% for post in site.posts %}
{% if post.url contains "changelog" and post.url contains "proctor" %}
- [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}