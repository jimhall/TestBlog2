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
{% endfor %}
</ul>

<a href="https://twitter.com/intent/tweet?screen_name=TwitterDev&ref_src=twsrc%5Etfw" class="twitter-mention-button" data-show-count="false">Tweet to @TwitterDev</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
