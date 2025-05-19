---
title: Changelog
layout: home
nav_order: 1
parent: Dev Notes
---

Below is a complete list of changelogs, sorted by newest to oldest.

{% for post in paginator.posts %}
{% if post.url contains "changelog" and post.url contains "proctor" %}
- [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

{% if paginator.previous_page %}
[Previous]({{ paginator.previous_page_path }})
{% endif %}
Page #`{{ paginator.page }}`
{% if paginator.next_page %}
[Next]({{ paginator.next_page_path }})
{% endif %}