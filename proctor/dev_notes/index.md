---
title: Dev Notes
layout: home
nav_order: 1
parent: Proctor
---

# Developer Notes

This is where the changelog and known issues are located.

## Changelog

This list is updated only when a new patch is released. Last patch date: PLACEHOLDER

{% for post in site.posts limit:10 %}
{% if post.url contains "changelog" and post.url contains "proctor" %}
- [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

[Show more...]({{ site.url }}/proctor/dev_notes/changelog)

## Known Issues

⚠️ COMING SOON ⚠️