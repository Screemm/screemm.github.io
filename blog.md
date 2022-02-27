---
title: Blog
layout: default
filename: /blog
---

<div class="container-fluid">
            <!-- COMMENT -->
            <div class="container" style="margin-top: 20px;">
                <div class="row row-cols-3 row-cols-md-3 row-cols-sm-1 g-4">
                    {% for post in site.posts %}
                        {% if post.tags contains "projects" or post.tags contains "index" %}

                        {% else %}
                            <div class="col">
                                <div class="card" aria-hidden="true">
                                    <img src="assets/images/{{ post.img }}" class="card-img-top" alt="{{ post.title }}">

                                    <div class="card-body">
                                        <h5 class="card-title" style="color: initial;">{{ post.title }}</h5>
                                        <p class="card-text" style="color: initial;">
                                            <span class="col-8" style="color: initial;">{{ post.excerpt }}</span>
                                        </p>
                                        <a href="{{ post.url }}" class="btn btn-primary">Go To Post</a>
                                    </div>
                                    <div class="card-footer">
                                        <small class="text-muted">Author - {{ post.author }} |</small>
                                        <small class="text-muted">{{ post.date | date: "%d %b, %Y" }}</small>
                                    </div>
                                </div>
                            </div>
                        {% endif %}
                    {% endfor %}
                </div>
                
                {%- include footer.html -%}
            </div>
        </div>
