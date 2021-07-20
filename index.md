---
title: Home
layout: template
filename: /
---

# Test
Testy McTesterson

{% for post in site.posts %}
    <div class="posts-summary">
        <a href="{{ post.url }}"><h6>{{ post.title }}</h6></a>
        <p>{{ post.excerpt }}</p>
    </div>
{% endfor %}
