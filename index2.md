---
layout: default2
title: Welcome to my blog
---

<!-- Begin code @ index2.md -->

# Welcome to my blog

I'm glad you are here. I plan to talk about ...

stuff

<div class="container">
<!--  <svg class="svg-footicon green"> -->
  <svg>
  <use xlink:href="{{ '/assets/favicon/jh-favico.svg' | relative_url }}"></use>
  </svg>
</div>

![jimhall](/TestBlog2/assets/favicon/jh-favico.svg)

This is the second pathetic attempt to add content and figure out how Jekyll
works.

<ul>
{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url | relative_url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  <p>{{ post.content | strip_html | truncatewords:50 }}</p>
{% endfor %}
</ul>

<!-- End code @ index2.md -->
