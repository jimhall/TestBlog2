---
layout: default
title: Welcome to my blog
---

# Welcome to my blog

I'm glad you are here. I plan to talk about ...

This is the second pathetic attempt to add content and figure out how Jekyll
works.

<ul>
{% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url | relative_url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    <p>{{ post.content | strip_html | truncatewords:50 }}</p>
{% endfor %}
</ul>
