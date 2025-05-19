---
title: Dev Notes
layout: home
nav_order: 1
---

# Developer Notes

This is where the changelog and known issues are located.

## Changelog

This list is updated only when a new patch is released. Last patch date: PLACEHOLDER

{% for post in site.posts %}
    {% if post.tags contains "changelog" %}
        - [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}
## Known Issues

⚠️ COMING SOON ⚠️